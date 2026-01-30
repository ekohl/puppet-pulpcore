# This file is managed centrally by modulesync
#   https://github.com/theforeman/foreman-installer-modulesync

source 'https://rubygems.org'

gem 'openvox', ENV.fetch('OPENVOX_GEM_VERSION', "~> 8.0"), :require => false, :groups => [:development, :test]
gem 'rake'

gem 'kafo_module_lint', {"groups" => ["test"]}
gem 'puppet-lint-spaceship_operator_without_tag-check', '~> 1.0', {"groups" => ["test"]}
gem 'voxpupuli-test', '~> 13.0', {"groups" => ["test"]}
gem 'github_changelog_generator', '>= 1.15.0', {"groups" => ["development"]}
gem 'puppet_metadata', '~> 6.0'
gem 'puppet-blacksmith', '>= 6.0.0', {"groups" => ["development"]}
gem 'voxpupuli-acceptance', '~> 4.1', {"groups" => ["system_tests"]}

# vim:ft=ruby
