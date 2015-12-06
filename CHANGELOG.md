# Change Log

## 1.0.2 (2015-12-06)
### Fixed
- works with sshkit 1.8

## 1.0.1 (2015-11-12)
### Fixed
- setting ssh hostname through `ssh_options`
- use login shell

### Feature
- log ssh command before it is being executed

## 1.0.0 (2015-08-01)
### Fixed
- removed dependency on capistrano-rails gem setting propper rails_env
- setting ssh port through `ssh_options`
- setting ssh user through `ssh_options`
- require a minimum version of 3.1.0 for capistrano (sshkit compatibility)

### Feature
- support for ssh keys

## 0.5.2 (2015-04-02)
### Fixed
- removed rails binary check due to different environments in sshkit and the ssh shellout

## 0.5.1 (2015-04-01)
### Fixed
- missing ssh proxy options in console task
