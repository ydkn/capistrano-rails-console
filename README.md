# Capistrano::Rails::Console

Remote rails console for capistrano

## Installation

Add this line to your application's Gemfile:

    gem 'capistrano', '~> 3.0.0'
    gem 'capistrano-rails-console'

And then execute:

    $ bundle

Or install it yourself as:

    $ gem install capistrano-rails-console

## Usage

Require in `Capfile` to use the default task:

    require 'capistrano/rails/console'

This will add a task `rails:console`:

    $ cap production rails:console

## Contributing

1. Fork it
2. Create your feature branch (`git checkout -b my-new-feature`)
3. Commit your changes (`git commit -am 'Add some feature'`)
4. Push to the branch (`git push origin my-new-feature`)
5. Create new Pull Request
