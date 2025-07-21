Execute the following commands to install the toolchain, QEMU and GDB

sudo apt update -y
sudo apt install -y gcc-riscv64-unknown-elf qemu-system-misc gdb-multiarch

for installing GBD DashBoard use the below given CMD
Just place .gdbinit in your home directory, for example with:

wget -P ~ https://github.com/cyrus-and/gdb-dashboard/raw/master/.gdbinit

Optionally install Pygments to enable syntax highlighting:

pip install pygments

if u want to exit from QEMU Press Ctrl+A and then X.
and if you want to exit from GDB press q and enter 
