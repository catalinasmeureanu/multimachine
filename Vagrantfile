Vagrant.configure("2") do |config|

  (1..2).each do |i|
    config.vm.define vm_name="web#{i}" do |node|
      node.vm.box = "csmeureanu/ubuntu-1604-vbox"
      node.vm.hostname = vm_name
    end
  end
 
end