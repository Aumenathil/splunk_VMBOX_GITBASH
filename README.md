# splunk_VMBOX_GITBASH
troubleshooting

Antonio@Slate MINGW64 ~
$ ls
 AppData/
'Application Data'@
 Cookies@
 Documents/
 Downloads/
 iCloudDrive/
 IntelGraphicsProfiles/
'Local Settings'@
'My Documents'@
 NetHood@
 ntuser.dat
 ntuser.dat.log1
 ntuser.dat.log2
 NTUSER.DAT{41483dc9-ea93-11eb-975c-00155d56cd1c}.TM.blf
 NTUSER.DAT{41483dc9-ea93-11eb-975c-00155d56cd1c}.TMContainer00000000000000000001.regtrans-ms
 NTUSER.DAT{41483dc9-ea93-11eb-975c-00155d56cd1c}.TMContainer00000000000000000002.regtrans-ms
 ntuser.dat{a34f9869-ec06-11ec-978a-80b65519f77b}.TM.blf
 ntuser.dat{a34f9869-ec06-11ec-978a-80b65519f77b}.TMContainer00000000000000000001.regtrans-ms
 ntuser.dat{a34f9869-ec06-11ec-978a-80b65519f77b}.TMContainer00000000000000000002.regtrans-ms
 ntuser.ini
 OneDrive/
 PrintHood@
 Recent@
 SendTo@
'Start Menu'@
 Templates@
 VMSetup/

Antonio@Slate MINGW64 ~
$ ls
 AppData/
'Application Data'@
 Cookies@
 Documents/
 Downloads/
 iCloudDrive/
 IntelGraphicsProfiles/
'Local Settings'@
'My Documents'@
 NetHood@
 ntuser.dat
 ntuser.dat.log1
 ntuser.dat.log2
 NTUSER.DAT{41483dc9-ea93-11eb-975c-00155d56cd1c}.TM.blf
 NTUSER.DAT{41483dc9-ea93-11eb-975c-00155d56cd1c}.TMContainer00000000000000000001.regtrans-ms
 NTUSER.DAT{41483dc9-ea93-11eb-975c-00155d56cd1c}.TMContainer00000000000000000002.regtrans-ms
 ntuser.dat{a34f9869-ec06-11ec-978a-80b65519f77b}.TM.blf
 ntuser.dat{a34f9869-ec06-11ec-978a-80b65519f77b}.TMContainer00000000000000000001.regtrans-ms
 ntuser.dat{a34f9869-ec06-11ec-978a-80b65519f77b}.TMContainer00000000000000000002.regtrans-ms
 ntuser.ini
 OneDrive/
 PrintHood@
 Recent@
 SendTo@
'Start Menu'@
 Templates@
 VMSetup/

Antonio@Slate MINGW64 ~
$ ls
 AppData/
'Application Data'@
 Cookies@
 Documents/
 Downloads/
 iCloudDrive/
 IntelGraphicsProfiles/
'Local Settings'@
'My Documents'@
 NetHood@
 ntuser.dat
 ntuser.dat.log1
 ntuser.dat.log2
 NTUSER.DAT{41483dc9-ea93-11eb-975c-00155d56cd1c}.TM.blf
 NTUSER.DAT{41483dc9-ea93-11eb-975c-00155d56cd1c}.TMContainer00000000000000000001.regtrans-ms
 NTUSER.DAT{41483dc9-ea93-11eb-975c-00155d56cd1c}.TMContainer00000000000000000002.regtrans-ms
 ntuser.dat{a34f9869-ec06-11ec-978a-80b65519f77b}.TM.blf
 ntuser.dat{a34f9869-ec06-11ec-978a-80b65519f77b}.TMContainer00000000000000000001.regtrans-ms
 ntuser.dat{a34f9869-ec06-11ec-978a-80b65519f77b}.TMContainer00000000000000000002.regtrans-ms
 ntuser.ini
 OneDrive/
 PrintHood@
 Recent@
 SendTo@
'Start Menu'@
 Templates@
 VMSetup/

Antonio@Slate MINGW64 ~
$ ls
 AppData/
'Application Data'@
 Cookies@
 Documents/
 Downloads/
 iCloudDrive/
 IntelGraphicsProfiles/
'Local Settings'@
'My Documents'@
 NetHood@
 ntuser.dat
 ntuser.dat.log1
 ntuser.dat.log2
 NTUSER.DAT{41483dc9-ea93-11eb-975c-00155d56cd1c}.TM.blf
 NTUSER.DAT{41483dc9-ea93-11eb-975c-00155d56cd1c}.TMContainer00000000000000000001.regtrans-ms
 NTUSER.DAT{41483dc9-ea93-11eb-975c-00155d56cd1c}.TMContainer00000000000000000002.regtrans-ms
 ntuser.dat{a34f9869-ec06-11ec-978a-80b65519f77b}.TM.blf
 ntuser.dat{a34f9869-ec06-11ec-978a-80b65519f77b}.TMContainer00000000000000000001.regtrans-ms
 ntuser.dat{a34f9869-ec06-11ec-978a-80b65519f77b}.TMContainer00000000000000000002.regtrans-ms
 ntuser.ini
 OneDrive/
 PrintHood@
 Recent@
 SendTo@
'Start Menu'@
 Templates@
'VirtualBox VMs'/
 VMSetup/

Antonio@Slate MINGW64 ~
$ cd Documents/Cybersecurity-Bootcamp/Linux-Module/

Antonio@Slate MINGW64 ~/Documents/Cybersecurity-Bootcamp/Linux-Module
$ ls
Vagrantfile

Antonio@Slate MINGW64 ~/Documents/Cybersecurity-Bootcamp/Linux-Module
$ vagrant up
Bringing machine 'default' up with 'virtualbox' provider...
==> default: Importing base box 'cybersecurity/UbuntuVM'...
==> default: Matching MAC address for NAT networking...
==> default: Checking if box 'cybersecurity/UbuntuVM' version '1.2.7' is up to date...
==> default: Setting the name of the VM: Linux-Module_default_1670092387185_39872
Vagrant is currently configured to create VirtualBox synced folders with
the `SharedFoldersEnableSymlinksCreate` option enabled. If the Vagrant
guest is not trusted, you may want to disable this option. For more
information on this option, please refer to the VirtualBox manual:

  https://www.virtualbox.org/manual/ch04.html#sharedfolders

This option can be disabled globally with an environment variable:

  VAGRANT_DISABLE_VBOXSYMLINKCREATE=1

or on a per folder basis within the Vagrantfile:

  config.vm.synced_folder '/host/path', '/guest/path', SharedFoldersEnableSymlinksCreate: false
==> default: Clearing any previously set network interfaces...
==> default: Preparing network interfaces based on configuration...
    default: Adapter 1: nat
==> default: Forwarding ports...
    default: 22 (guest) => 2222 (host) (adapter 1)
==> default: Booting VM...
==> default: Waiting for machine to boot. This may take a few minutes...
    default: SSH address: 127.0.0.1:2222
    default: SSH username: vagrant
    default: SSH auth method: private key
==> default: Machine booted and ready!
==> default: Checking for guest additions in VM...
    default: The guest additions on this VM do not match the installed version of
    default: VirtualBox! In most cases this is fine, but in rare cases it can
    default: prevent things such as shared folders from working properly. If you see
    default: shared folder errors, please make sure the guest additions within the
    default: virtual machine match the version of VirtualBox you have installed on
    default: your host and reload your VM.
    default:
    default: Guest Additions Version: 6.0.14
    default: VirtualBox Version: 6.1
==> default: Mounting shared folders...
    default: /vagrant => C:/Users/Antonio/Documents/Cybersecurity-Bootcamp/Linux-Module

Antonio@Slate MINGW64 ~/Documents/Cybersecurity-Bootcamp/Linux-Module
$ cat Vagrantfile
# -*- mode: ruby -*-
# vi: set ft=ruby :

Vagrant.configure("2") do |config|
  config.vm.box = "cybersecurity/UbuntuVM"

  config.vm.provider "virtualbox" do |vb|
    # Display the VirtualBox GUI when booting the machine
    # Uncomment ONE the lines below to control how much RAM Vagrant gives the VM
    # We recommend starting with 4096 (4Gb), and moving down if necessary
    # vb.memory = "1024" # 1Gb
    # vb.memory = "2048" # 2Gb
    # vb.memory = "4096" # 4Gb
    vb.gui = true
  end
end
