# Lecture outline
---------------------

## Linux
> Everything is a file

> Different flavours (ubuntu, CentOS, RHEL)

> So if you want to modify something, just edit the file

> Programs are just a collection of files

> In a place your computer knows where to look

> So we will talk about basic commands and then how install your own program

> terminal vs shell....different shells (Bash/ksh and csh/zsh/tcsh)

## try using the basic commands walkthrough
> `cd ls cp mv echo export which time tar touch man clear diff head cat tail more pwd`

> `find sed awk git ln rsync scp ftp wget curl chmod chown kill  grep top convert latex`

> These basic commands are just files found within a certain directory

> (use which to find them)

> The directory is specified via PATH

> Any directory found on path is searched for executables

## installing programs without root 
> so lets install a program without root

> remember everything is a file in a certain location

> open `installingYourOwnProgram.sh` and follow along

> this is called compiling from source

> set INSTALL_LOCAL to a location you want to install programs at (~/programs/)

> walk through file

> another semi-auto way is `installprogram.sh`

> so now we just need to update your path to point at this location

> now we have a working python. You can follow this same logic for other languages

## SSH and VNC
> next to get onto the nhn systems

> `ssh username@login.nhn.ou.edu` <- works anywhere

> `ssh username@gradlab.nhn.ou.edu` <- works on campus and at local ISP

> once inside you can go to a certain machine via ssh bohr

> if you have a personal workstation you can ssh directly to it

> `ssh username@computer.nhn.ou.edu`

> use `ssh -XY` to get GUI

> good for quick options

> better option use vnc

> on host computer use `vncserver`

> then on client use `vncviewer -via host host:1`

> local -> remote

> `scp local username@host:remote`

> remote -> local 

> `scp username@host:remote local`

## Connecting Laptop via wifi
> If you have ubuntu/ mint/ rhel / centos should already have the needed template

> just try to connect and see if it works.

> All other Linux Flavours might need a wifi-config file 

> included a config `wlp2s0-WIFI@OU`

# end of file
