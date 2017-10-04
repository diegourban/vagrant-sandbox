Vagrant.configure("2") do |config|
  # if you already downloaded the box
  # vagrant box add --name precise32 /home/urban/boxes/precise32.box
  # config.vm.box = "precise32"

  # or vagrant will download it
  # if you are under proxy: export http_proxy=http://user:password@address:port
  config.vm.box = "http://files.vagrantup.com/precise32.box"
  config.vm.define :web do |web_config|
    web_config.vm.network "private_network", ip: "192.168.50.10"
  end
end
