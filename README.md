# Linux

The shell is a part of the operating system which defines how the terminal behaves.

  echo $SHELL --> /bin/bash (bash shell is Borne again shell)

## Shortcuts
Left and Right Arrows bring up commands typed earlier in terminal
Tab helps in completion

## Navigation

  pwd --> /home/dhruba (print working directory)
  ls --> (list - outputs what is in our current location)

  ls -l --> (long listing, 1st character says if it is a file represented by - or directory by d, next 9 characters is permissions, next field is number of blocks,
  next field is owner of file or directory, next field is the group the file or directory belons to - users, then file size, modification time, actual name of file 
  or directory)
  total 44
  drwxr-xr-x 2 dhrub123 dhrub123 4096 May 27 20:08 Desktop
  drwxrwxr-x 6 dhrub123 dhrub123 4096 Jun 16 19:21 DockerImages
  drwxr-xr-x 2 dhrub123 dhrub123 4096 May 27 20:08 Documents
  drwxr-xr-x 2 dhrub123 dhrub123 4096 May 30 23:37 Downloads
  drwxrwxr-x 3 dhrub123 dhrub123 4096 May 27 20:45 Git
  drwxrwxr-x 3 dhrub123 docker   4096 Jun 17 14:30 kubernetes
  drwxr-xr-x 2 dhrub123 dhrub123 4096 May 27 20:08 Music
  drwxr-xr-x 2 dhrub123 dhrub123 4096 May 27 20:08 Pictures
  drwxr-xr-x 2 dhrub123 dhrub123 4096 May 27 20:08 Public
  drwxr-xr-x 2 dhrub123 dhrub123 4096 May 27 20:08 Templates
  drwxr-xr-x 2 dhrub123 dhrub123 4096 May 27 20:08 Videos

  ls kubernetes --> lists out content in kubernetes directory
  ls -l kubernetes --> 
  total 4
  drwxrwxr-x 37 dhrub123 docker 4096 Jun 17 14:30 k8s-specs

## Paths

There are 2 types of paths - absolute and relative.
The Linux file system ahs a hierarchichal structure at the root of which is /. It has many directories and subdirectories.
So absolute path will begin with a / and relative path is the path in relation to the location we are currently at.

  ~(Tilde) refers to home directory -- echo ~ --> /home/dhruba
  .(Dot) refers to current directory
  ..(DotDot) refers to parent directory, so if I at /home/dhruba. doing ls ../../ will list contents of root folder
  / is the root directory

  cd / --> takes us to root and cd is change directory
  /etc -- has config files
  /var/log -- stores log files
  /bin and /usr/bin -- stores programs



