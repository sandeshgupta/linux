# Assignment 1

### Question 1 

Did by myself
 
### Question 2 - Steps followed

- Configure GCP VM instance
- Install `build_essential`, `gcc` and `make` 
- Clone the repo `torvals/linux` in VM
- Upload cmpe283.c and Makefile file to VM
- `make menuconfig`
- `make oldconfig`
- `make prepare`
- `make -j 8`
- `sudo make INSTALL_MOD_STRIP=1 modules_install`
- `sudo make install`
- `sudo reboot`
- `uname -a`
- `make`
- Add the licence info in c file and save
- `make`
- `sudo insmod cmpe283-1.ko`
- `dmesg`
- Update the code to get Entry, Exit, Primary, Secondary controls
- `make; sudo rmmmod cmpe283-1`
- `sudo insmod cmpe283-1.ko`
- `dmesg`
- Push the changed files and the output images to repo
