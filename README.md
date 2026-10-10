About
-----
This is a set of exercises to learn linux, designed by ENIGMA club, IIITS.

Requirements
------------
* Necessary:
    * bash interpreter

* For audio (Optional):
    * Internet connection  
    * mpv
    * [ For linux users ]: Sound firmware 

Help
----
* Start by installing the [Requirements](#requirements)
* On debian based systems (ubuntu/mint/etc.):
  ```bash
    sudo apt install mpv yt-dlp ffmpeg git
  ```
* On arch based systems:
  ```bash
    sudo pacman -S mpv yt-dlp ffmpeg git
  ```
* On fedora:
  ```bash
    sudo dnf install mpv yt-dlp ffmpeg git
  ```
* On void:
  ```bash
    sudo xbps-install -S mpv yt-dlp ffmpeg git
  ```
* :( for other distros.

&nbsp;

You should know these commands before starting (You do not need to know alternative forms of these commands before starting):

* Print Working Directory: What directory you are currently in. This is the start of all relative paths.
``` 
    pwd 
```

&nbsp;

* List the files and folders in the working directory
``` 
    ls
```

&nbsp;

* Change the working directory. <directory> is either a absolute or relative path.
``` 
    cd <directory>
```

&nbsp;

* Print the contents of filename on the terminal.  
```
    cat <filename>
```

&nbsp;

After you have these prepared:
Make a copy of this repo and move into it:

> [ NOTE: FOR WSL USERS ]

> Make sure while running the following commands you are in the linux filesystem

> i.e.  `pwd` MUST NOT start with /mnt/

```
git clone https://github.com/ramak1618/enigmalings
cd enigmalings
```

&nbsp;

Then you may check audio using:
```
./test.sh
```
Note: Audio might have startup delay and/or get stuck depending on your internet connection

&nbsp;

Get your first exercise:
```
cat help.txt
```

License
-------
The bash scripts (.sh files) in this repository are licensed to public domain under [CC0 License][licenselink]

**This license DOES NOT apply to any third-party media / memes referenced, or any audio used.**

All external media assets are referenced strictly for education/transformative purposes.

Source Credits can be found in respective directories.


[licenselink]: LICENSE
