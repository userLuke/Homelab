# ESXi Installation Guide  

## First things to do  
- Use [VMWare's Compatibility Guide](https://www.vmware.com/resources/compatibility/search.php) to verify guaranteed compatibility and which version of VMWare you should download  
- Download your version of ESXi vSphere that is right for you
- Verify your downloaded image, here is a [Guide from VMWare](https://www.vmware.com/download/cryptographichashes.html)
- Create a bootable USB, the easiest way to do this is Rufus on Windows or balenaEtcher on \*nix  
- You have everything you need to get started with the actual installation
  
## Boot and Install  
- Plug in your bootable media and power on your machine, depending on your boot settings you may need to configure BIOS to assist you in booting from USB/CD etc.
- Once successfully booted into the ESXi Installer, you will see something like this  
![image](https://user-images.githubusercontent.com/54081466/86535089-bd219080-beab-11ea-8ab2-7ce3e3273bc4.png)  
- Then, you must accept the EULA or you cannot cont
- Press continue and you will be prompted as to where you would like to install, as you can see below I chose my USB drive as I will be booting from that, normally
![image](https://user-images.githubusercontent.com/54081466/86535210-ab8cb880-beac-11ea-9927-44e208dc2573.png)
- On the next couple screens you will choose a keyboard layout, root password (make sure this is a strong password and if you cannot remember it then you may write it down, however, I recommend you use a password manager, such as [BitWarden](https://bitwarden.com/)
- Now, confirm the installation configurations and the installer will begin to partition the disk
![image](https://user-images.githubusercontent.com/54081466/86535257-176f2100-bead-11ea-882f-f5396f8b2098.png)
- Finally, you will be presented with this screen
![image](https://user-images.githubusercontent.com/54081466/86535277-34a3ef80-bead-11ea-8d06-8ec5d3460458.png)
- As the prompt states, make sure to remove the installation media before restarting, so that you do not boot bake into the installer but ESXi itself


