# ZonamaDev

Zonama - The living planet, or in our world an easily deployed development environment for working on the server code of swgemu's Core3 (https://www.swgemu.com/)

## Windows Host

#### Minimum requirements
- Virtualization enabled cpu (Check your BIOS if virtualbox fails to boot box)
- 2 Cores
- 2G Ram
- Dynamically sized 40G HD (Approx 15G on first boot) (Usually $HOME/ZonamaDev)
- 2.5Gb in your $HOME directory for base box image (On windows this is usually C:\ )

### Fast Start

#### Downloads
* Github's Git for Windows: https://git-for-windows.github.io/
* VirtualBox for Windows: https://www.virtualbox.org/wiki/Downloads
* Vagrant for Windows: https://www.vagrantup.com/downloads.html
 
#### Bootstrap
Launch Git Bash: Start -> Programs -> Git Bash
or
Right click in desired directory -> Git Bash

Type:
````
curl -L http://downloads.lordkator.com/bootstrap.sh | bash
````

Watch for instructions.

#### Hard way

Type:
````
git clone https://github.com/lordkator/ZonamaDev.git
cd ZonamaDev/fasttrack
./setup.sh
````

Watch for instructions.
