
<p align="center"><img align="center"  src="https://user-images.githubusercontent.com/67634565/135770396-bc4474c0-2a57-4e53-a076-f4ae3d2fb409.png" width='270px' ></p>

<h1 align="center">stowthemer</h1>
<h3 align="center">A quick script to manage <a href="https://github.com/umgbhalla/dotstow">dotstow</a></h3>

#

### Todo

- [x] CONTRIBUTING.md
- [ ] yml/toml config generator/parser [res0](https://perfecto25.medium.com/handle-bash-config-file-variables-like-a-pro-957dc9a838ed)
 [res1](https://unix.stackexchange.com/questions/175648/use-config-file-for-my-shell-script) [res2](https://askubuntu.com/questions/743493/best-way-to-read-a-config-file-in-bash)
- [ ]  menu for theme and subtheme selection system
    - [ ] [smenu](https://github.com/p-gen/smenu)
    - [ ] [pure bash menu thingy](https://serverfault.com/questions/144939/multi-select-menu-in-bash-script/506704#506704)
    - [ ] [python module for menu system](https://medium.com/geekculture/build-interactive-cli-tools-in-python-47303c50d75)
    - [ ] [rusty dialog](https://docs.rs/dialoguer/0.8.0/dialoguer/)
- [ ] tests
- [ ] rofi/fzf wrapper
- [ ] [yad](https://github.com/v1cont/yad) wrapper (GUI)
- [ ] support for more window manager
- [ ] package for aur

# Structure
yml config  will contain 

- entities (app's .config/\* folder name) paried with a prime number
- themes name and prime product of its objects
- inter theme breaking/compatibility analysis is done by product of entities in theme 
- flags 
	 - -a $@ , apply themes named in $@
	 - -g , get current theme and prime configuration
	 - -i , init function
	 - -m , make current prime config into a theme 
	 - -c , clear all symlinks \* risk



  
## Please make PR for Feature request, Development of this script has not yet started


<p align="center"><img align="center"  src="https://user-images.githubusercontent.com/67634565/125792404-8feb3087-2884-42c8-9432-024879a9b3fc.gif" width='270px' ></p>
