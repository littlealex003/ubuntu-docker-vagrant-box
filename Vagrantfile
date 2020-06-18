Vagrant.configure("2") do |config|
  config.vm.provider "docker" do |d|
#    d.image = "jess/chrome"
    d.build_dir = "."
#    d.create_args = ["--privileged", "-e","DISPLAY=unix:0"]
    d.name = "ubuntu_base"
#    d.volumes = ["/tmp/.X11-unix:/tmp/.X11-unix"]
  end
end