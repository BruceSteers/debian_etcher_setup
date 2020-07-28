# debian_etcher_setup
configure pkexec and create a desktop launcher for balenaEtcher.AppImage on Debian

This is a simple setup script for getting the Etcher.AppImage working on Debian Systems.

Written by Bruce Steers

Requirements:
zenity (already included in most distros if not "sudo apt-get install zenity")

The latest excellent balenaEtcher.AppImage file 
downloaded from https://www.balena.io/etcher/


How to use...
github method...

From a non-root terminal type the following..
<CODE><p>
git clone https://github.com/BruceSteers/debian_etcher_setup<p>
cd ./debian_etcher_setup<p>
chmod +x ./Setup_Etcher<p>
sudo ./Setup_Etcher<p>
</CODE>

You will be asked to provide the path to your downloaded balenaEtcher.AppImage file
Then a pkexec policy will be added to the system for it and a desktop launcher created

Many Thanks to the balena team for making such an excellent application and
letting us having it for free.

Also thanks to whoever owns the Icon Image.

Have fun Etching :)

