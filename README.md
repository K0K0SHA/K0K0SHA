## Hello
Nice to meet you. I'm basically a sysadmin who got carried away with hacking. GitHub serves as a primary document+codebase for my public research projects. I doubt any of this will be seen by many people, besides glowie dragnets. I guess that's good, because you could easily crash any system just by cloning my repos. And most networks. In fact, you should probably go away. Oh, and I also hate technology. Most code I write is thus destructive in nature. 

# My Repos
My Repo Descriptions  
__import repo__ example: __import miscX__

## miscX 
---------------------------------------------------------------------
If you want a "creme de la creme" demonstration of what my GitHub repo has, I say you should just download and run miscX.py and see for yourself. The miscX library just has so many useful functions. It could save you a LOT of time doing things yourself. I tried to code that library as well as I could. I put exception handling everywhere too, although Python probably has that built in already. All you need is that one file, and you can program much faster. Especially if you have autocomplete in your Python editor or IDE. To sum it up, miscX is everything i wish Python could do automatically. But now it can.

Compatibility-wise, miscX is highly optimized towards my personalized development environment and programming style. I prefer to run a lot of bash terminal commands, so that's what most of miscX starts as. However, miscX is python3 code, so it is cross-platform. miscX is capable of running on any OS which has python3, but it's mostly tested on Linux Mint and Windows 11. A shell script should also run on Android if you're running Termux, and on Mac if you're running Bash. The compatibility issues come up if you try to interact with the OS in some way. Check out the part about the miscX network later for more info on that.

miscX is capable of...  
-checking its permission to see the level (prototype-phase: Linux root only)
-OS identification using platform library, used for ensuring proper development environment.  
-dependency checking and installation, bash-only (mac+and+linx)  
-safe command execution with exception handling based on output using os.system()  
-verbose command execution, with the same built-in safety  
-file operations such as checking if a file exists, creating a file, reading a file line-by-line, etc always __WITH EXCEPTION HANDLING__  
-allowing users to choose from a list, or confirm/deny using inquirer for K0K0$H@'s preferred TUI (in-terminal menu, classic style)  

malware built atop miscX, by just import the module (code not on GitHub because this code is far too cool for you)  
-OS identification is powerful in malware. Python has os library, which is bad for identification. So, miscX uses the recommended platform module instead.  
-pwn using remote installation with git or apt-get install if a Linux machine is detected  
-pwn using remote installation with pkg if Android or Termux is detected  
-pwn using Powershell choco --> git if Powershell is detected (project choco_pwn)   
-check dependency, then pwn dependency. Like Metasploit, but better. K0K0$H@ 'sploit!!! Seriously though, future Metasploit module incoming  
-Session DoS Linux user with forkbomb (check out my fork bomb repo)  
-DOS DNS on current default gateway on a common port, bringing down a local network (check out my evil repo, eg evil/DDOS)  

todo miscX  
-add amon for 802.11  
-add gcc compiler script  
-add Java script
-create 'non-dangerous' version of miscX  
  
## custom desktop repo
It can set up a wallpaper and Conky on your desktop. It depends on miscX to download and install Conky. The goal is to give you a lightweight yet informative display which looks cool, and which works on Ubuntu and Mint. Most people are saying it's extremely ugly. I can only say that it's supposed to be that way. Then again, I need to make Conky behave better. Not that my target audience is big to begin with here. What works in Cinammon doesn't always work in GNOME. The original idea was simple: I just wanted to install an Android-like widget onto Linux Mint. 
I ran into a few issues with this whole process. First, Conky's syntax. It wasn't impossible to read, but trying to do logic with it was hard.   
  
