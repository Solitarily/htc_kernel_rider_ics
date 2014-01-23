--Please follow below command to download the official android toolchain: (arm-eabi-4.4.3)
        
                git clone https://android.googlesource.com/platform/prebuilt

                NOTE: the tool ¡¥git¡¦ will need to be installed first; for example, on Ubuntu, the installation command would be: apt-get install git

--Modify the .bashrc to add the toolchain path, like bellowing example:

								PATH=/usr/local/share/toolchain-eabi-4.4.3/bin:$PATH 

--Start 

								$make rider_defconfig
								$make 

--Clean
								$make clean

--Files path
arch/arm/boot/zImage
drivers/*/*.ko																
