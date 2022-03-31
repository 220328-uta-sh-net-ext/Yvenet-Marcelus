## History of Linux and shell
The shells have been around for quite some time, and it all started with the advent of the first UNIX shell. A man by the name of Ken Thompson created a shell that could be used by UNIX. 
•	Thompson developed the V6 shell in 1971. 
•	The shell (/bin/sh), an independent user program, had the capability to execute outside of the kernel environment.
•	Within the shell the “if” command could evaluate conditional expressions.   
•	The shell has a little under 900 lines of c source attributed to it. 
•	The shell allocated a compact syntax that redirected (< > and >>) and piped (| or ^). 
•	The shell supported and invoked sequential commands like (with ;) and the asynchronous commands like (with &). 
•	Thompson’s version, however, ultimately fell short of solidarity because of an inability to script. 
•	The shell’s purpose was to produce an interactive shell with the ability to invoke commands and finalize results for review. 
•	Linux was created in the year 1991 by a Finnish student named Linus Torvalds as a proposed project to create a new free operating system kernel.
•	 Today, Linux has updated several features on its platform that include the command substation and HERE documents that embed preserved string literals within a script. 
•	To date, Linux has managed to develop more than 23.3 million lines of source code 

## Getting Started with Shell Programming
The initial process of working with Shell programming requires you to choose from one of the following active shells. 
**Unix/Linux shell**
•	The Bourne Shell
•	The C Shell
•	The Korn Shell
•	The GNU Bourne-Again Shell
•	One of the other Exotic Shells
The typical operations performed by shell scripts include file manipulation, program execution, and printing text. Shell scripts are computer program(s) created as an extension to interpreted by the Unix shell. These various dialects of shell scripting are considered to be scripting languages. These script(s) also perform various tasks such as setting up environment(s), running program(s), and complete any necessary cleanup or logging.
The shell uses a command line prompt to manage many of its capabilities using shell commands. The following components are required to create a user-friendly environment, an updated operating system (Linux, etc.), a user interface (Shell), a Terminal (X Window, etc.), desktop manager such as (Linux desktop, etc.). Creating this environment will require the appropriate configuration to allow for the best computing experience.
**Creating a shell script (requirements)** 
•	Selecting a Text editor
•	Creating and preparing a file to be executed by the text editor
•	Saving the executable file to your text editor
•	Testing and move your script to the production environment
•	Opening your text editor
**A Few Text Editor Command**
•	Open file: vi filename
•	Edit mode: press ESC and type I
•	Command mode: press ESC
•	Save file: press ESC and type :w filename
•	Save file and quit: press ESC and type :wq

## The Shell Variables and Environment
A shell variable also referred to as a n environment variable is a dynamic-named value has the capability to affect the way running processes operate. They’re apart of the environment in which a process runs. Variables can be used to for options like storing data or configuring other options. There are two different types of variables, a system variable, and a user defined variable.
**System Variables**
•	set
•	env
•	printenv
Below are a few examples of commonly used shell variables.
**Shell Variables** 
**System Variables**
•	BASH_VERSION
•	HOSTNAME
•	CDPATH
•	HISTFILE
**System Variables-Variable Value Type**
•	echo $BASH_VERSION
•	echo $HOSTNAME
•	echo $CDPATH
•	echo $HISTFILE
**User Defined Variables**
*These variables are created and maintained by system user and uses any valid variable name. As a side note, it important to avoid using all the uppercase names available due to their usage by the shell system.
Shell Environment
In a shell environment there are a set of variables that are defined by the “login” program, the system initialization file, and the user initialization files. They are certain variables that are defined by default. In addition, a shell environment has two types of variables, an environment variable and a local (shell) variable.
**Environment Variable**
•	PATH
•	HOME
•	HOME/{>AppName}
•	USERPROFILE
•	TERM
**Shell Variable**
•	user
•	term
•	home 
•	path



