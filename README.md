[![Gem Version](https://img.shields.io/gem/v/capistrano-rails-console.svg)](https://rubygems.org/gems/capistrano-rails-console)
[![Dependencies](https://img.shields.io/gemnasium/ydkn/capistrano-rails-console.svg)](https://gemnasium.com/ydkn/capistrano-rails-console)
[![Code Climate](https://img.shields.io/codeclimate/github/ydkn/capistrano-rails-console.svg)](https://codeclimate.com/github/ydkn/capistrano-rails-console)

[![Join the chat](https://badges.gitter.im/Join%20Chat.svg)](https://gitter.im/ydkn/capistrano-rails-console)


# Capistrano::Rails::Console

[![Join the chat at https://gitter.im/ydkn/capistrano-rails-console](https://badges.gitter.im/Join%20Chat.svg)](https://gitter.im/ydkn/capistrano-rails-console?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)

Remote rails console for capistrano

## Installation

Add this line to your application's Gemfile:

```ruby
gem 'capistrano-rails-console'
```

And then execute:

    $ bundle

Or install it yourself as:

    $ gem install capistrano-rails-console

## Usage

Require in `Capfile` to use the default task:

```ruby
require 'capistrano/rails/console'
```

This will add a task `rails:console`:

    $ cap production rails:console

You can also start a sandbox session:

    $ cap production rails:console sandbox=1

## Contributing

1. Fork it
2. Create your feature branch (`git checkout -b my-new-feature`)
3. Commit your changes (`git commit -am 'Add some feature'`)
4. Push to the branch (`git push origin my-new-feature`)
5. Create new Pull Request
