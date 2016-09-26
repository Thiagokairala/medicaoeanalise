Vagrant.configure("2") do |config|
  config.vm.box = "ubuntu/trusty64"

  config.vm.provision "shell", inline: <<-SHELL
    apt-get update
    apt-get install -y texlive-full abntex
  SHELL
end
