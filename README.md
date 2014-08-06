#Operating System U boot screen#

This is a simplified version of Operating System U boot screen.

This is a Ubuntu-derived work.

##Installation##
	git clone https://github.com/awmrozek/OSU_Simple_Plymouth.git
	cd OSU_Simple_Plymouth
	sudo mkdir /usr/share/plymouth/themes/osu-simple
	sudo cp -av * /usr/share/plymouth/themes/osu-simple/
	sudo plymouth-set-default-theme -R osu-simple
	sudo update-initramfs -u

##Switching##

Switching between the two installed themes can be easily accomplished by:

	sudo plymouth-set-default-theme -R osu
	sudo update-initrd -u

