require 'bundler/setup'
require 'kitchen/vagrant'

Vagrant::Config.run do |config|
  Kitchen::Vagrant.define_vms(config)
end
