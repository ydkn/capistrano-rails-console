# Change Log

## Unreleased
### Fixed
- removed dependency on capistrano-rails gem setting propper rails_env
- setting ssh port through `ssh_options`
- setting ssh user through `ssh_options`
- require a minimum version of 3.1.0 for capistrano (sshkit compatibility)

### Feature
- support for ssh keys

## 0.5.3 (2015-06-12)
### Fixed
- Add bundle command mapping check(this fixes console with RVM and other gems that map 'bundle' command)

## 0.5.2 (2015-04-02)
### Fixed
- removed rails binary check due to different environments in sshkit and the ssh shellout

## 0.5.1 (2015-04-01)
### Fixed
- missing ssh proxy options in console task
