## Hello
Nice to meet you. I'm just a sysadmin who got carried away with hacking. GitHub serves as a primary document+codebase for my public research projects. I doubt any of this will be seen by many people, besides glowie dragnets. I guess that's good, because you could easily crash any system just by cloning my repos. And most networks. In fact, you should probably go away. Most code I write is thus destructive in nature. 

# My Repos
My Repo Descriptions  
Python import usage: __import repo__ example: __import miscX__  

## miscX 
---------------------------------------------------------------------
If you want a "creme de la creme" demonstration of what my GitHub repo has, I say you should just download and run miscX.py and see for yourself. The miscX library just has so many useful functions. It could save you a LOT of time doing things yourself. I tried to code that library as well as I could. I put exception handling everywhere too, although Python probably has that built in already. All you need is that one file, and you can program much faster. Especially if you have autocomplete in your Python editor or IDE. To sum it up, miscX is everything i wish Python could do automatically. But now it can.

Compatibility-wise, miscX is highly optimized towards my personalized development environment and programming style. I prefer to run a lot of bash terminal commands, so that's what most of miscX starts as. However, miscX is python3 code, so it is cross-platform. miscX is capable of running on any OS which has python3, but it's mostly tested on Linux Mint and Windows 11. A shell script should also run on Android if you're running Termux, and on Mac if you're running Bash. The compatibility issues come up if you try to interact with the OS in some way. Like how it's ifconfig on Linux and ipconfig on Windows.

__miscX is capable of...__  
-checking its permission to see the level (prototype-phase: Linux root only)  
-OS identification using platform library, used for ensuring proper development environment.  
-dependency checking and installation, bash-only (mac+and+linx)  
-safe command execution with exception handling based on output using os.system()  
-verbose command execution, with the same built-in safety  
-file operations such as checking if a file exists, creating a file, reading a file line-by-line, etc always WITH EXCEPTION HANDLING  
-allowing users to choose from a list, or confirm/deny using inquirer for K0K0$H@'s preferred TUI (in-terminal menu, classic style)  

malware built atop miscX:
-my primary work with 802.11 hacking uses miscX a lot.  
-OS identification is powerful in malware. Python has os library, which is bad for identification. So, miscX uses the recommended platform module instead.  
-pwn using remote installation with git or apt-get install if a Linux machine is detected  
-pwn using remote installation with pkg if Android or Termux is detected  
-pwn using Powershell choco --> git if Powershell is detected (project choco_pwn)   
-check dependency, then pwn dependency. Like Metasploit, but better. K0K0$H@ 'sploit!!! Seriously though, future Metasploit module incoming  
-Session DoS Linux user with forkbomb (check out my fork bomb repo)  
-DOS DNS on current default gateway on a common port, bringing down a local network (check out my evil repo, eg evil/DDOS)  
-ransomware test model (disk-encryption)  
-Android hardware-level disk encryption  

__todo miscX__  
-add amon for 802.11  
-add gcc compiler script  
-add Java compile/run/debug script  
-create 'non-dangerous' version of miscX  

## evil  
Examples of malware are found here, for research purposes. Most of this stuff is just scripts to launch stuff cloned from other repos, like the skiddie I am. But the modifications are the real thrill. How do I fork stuff here???

## Linux custom desktop repo
In Android or iOS, adding a desktop widget is quite easy. Why should Linux Desktop be any harder?
This repo can set up a wallpaper and Conky on your desktop. The original idea was simple: I just wanted to install an Android-like widget onto Linux Mint. Then, I made it informative. I ended up with something which was far better than the Conky default configuration. I love a widget that shows things like my public and private IP, disk space, etc. Lastly, I still plan to add customization toggles. In the long term, I plan to add an Android info widget repository. 

I ran into a few issues with this whole process. First, Conky's syntax. The Lua-style syntax wasn't easy to read, and trying to do logic with it was hard. Second, Conky is glitched. Comparison statements aren't getting the results they should, so resulting statements are going haywire. In this case, coloring is controlled by these statements. I am working on a fix to that, but I have no idea at all what is causing the problem.

The thing I can't fix so easily with my custom desktop is the compatibility. Now, obviously a custom desktop like this one isn't meant to run on Windows (although someday I might make it a widget.) There are two main issues with the compatibility of desktop widgets on Linux.  
-First, there is the Linux desktop environment itself. It can be GNOME, MATE, KDE, Cinnamon, or others.
-Second, there is the issue of configuration files and where they go. If Conky is installed on Arch, the configuration will be much different than the one installed on Mint. The main difference is syntax. Nothing a few find-replace scripts won't fix, in theory. But I never wanted to do all that work. I can't even make Conky work right now.

After the issues are finished, I want to allow user adjustment of Conky's transparency, and color themes. This repo needs to also have miscX monitor_select() function for configuration, in order to allow user selection of the monitor to display info on in the Linux custom Desktop. 

## project_pape
This is intended to be an automatic wallpaper changer for Linux. Sometimes, distros can be retarded about basic things like setting a folder to use wallpapers with. It's nothing special because this thing should already be in your settings. It has a hidden fork too, which comes with a certain built in "18+ theme" if you will. Totally can't post it here.  
Additionally, fully setting a theme could involve the optional installation of Conky using custom desktop, which would optionally go together with this repo. If the distro is the proper one. This particular repo is very distro-exclusive.

## fork bomb
Unironically just a fork bomb. This thing essentially belongs to no one, but I certainly want it on my page here. It's just a Linux meme. Crashes your session without damage(hopefully), if you're meme enough to run it. 

## stay_awake
Aims to be a cross-platform script for keeping the screen awake using the terminal. Made mostly for practice and convenience.

TODO:  
-personal public hacking journal link
