# COMMANDS AND SHORTCUTS
This is a quick-reference for commands in the linux shell.

#### Notes: 
	* The parenthesis in listed examples are optional
	* See command 'man' for more details and a complete list of command and command 		functionality.

## Command		
### cat		
		(direct/)filename1 ((direct/)filename2 (...(direct/)filenameN))			
		show document's or docuements' content concatenated

### cd	
		cd (..(/../)) (~) (directory-nane)
		move to directory
			
### cp	
		cp filename new-file-destination
		copy file from one place to another
		
### df 
		df (args) (filename)
		by default, lists all info about the file system on which each filename resides on. note -h for human-readable
 
### head	
		head filename
		show first X lines of a document
		
### hier
		a list of standard linux directories and a brief description of their purposes
	
### kill 
		kill (args) <pid>process
		kills the process (default is with code 15) with arg options.
	
### less	
		less filename
		prints file contents with more features than more	
		
### ln
		ln (args) filename
		can make hard or symbolic links to a file or directory.
	
### ls 	
		ls (directory-name)
		List current folders and files in a directory

### man	c
		man ommand			
		see documentation on the command of interest

### mkdir	
		mkdir directory-name (directory-path-if-different-from-current)
		makes a directory (at specified path)

### mv	
		mv filename destination-directory/new-filename
		move a folder or file to another directory
		
### nice
		nice (args) 

### pkill (pgrep)
		pkill (args) pattern
		looks up/ signals process(s) based on the name and other attributes
		
### ps
		ps (args)
		create a snapshot of the current processes

### pwd
		pwd
		"print working director" shows current directory from root
		
### renice
		renice (args) <pid> process
		the higher the arg assigned the lower the priority. The top priority is -20

### rm	
		rm (arguments) directory/filename
		remove an empty directory or a filename in a directory.

### signal
		a suite of commands to be operate on processes 
		
### strace 
		stack [many ards and options. Look it up man]
		used to run a command until it exits and much, much more for debugging/admin/diagnostics
		
### touch	
		touch (directory/)filename
		create a file at the driectory with default being current directory.

### w	
		w
		show logged-in users and their activities

## Arguements
### -r	(recursive)
		rm -r 
		would recusively remove files in a directory
		
### -f	(file)
		rm -rf 
		In the example. this would recursivly remove files(-r) and the folder(f)

## Programs
### htop	
		similar to task manager and top but has different functionality
		use the f# to get more options on what to do with running processes. The options associated
		with htop are already linux command line commands but integrated into a GUI.


### top 	
		sorts activitis like task manager. Can see process ID (PID) and use that info to 
		netstat -tupln is a command that shows network activity (run as root to get more info).
		
## Directories
### /bin
	system programs live here. Very useful.
	really handy to see programs
	
### /boot 
	kernal, bootloader (grub), and other kernal files.

### /dev 
	devices such as hard disk. 'sd' is the disk
	
### /etc
	all program configurations exist in here unless someone messed up and didn't coply to the 

### /home 
	this is where users live

### /lib
	32 bit programs

### /lib64
	64 bit programs

### /opt
	link from bin to opt as in optional files if you are making a program. 
	
### /proc
	among many other things, this directory gives information on dynamically-allocated files
	
### /root
	where root lives
	
### /sbin
	system programs used for booting not often used by users.
	
### /tmp
	temporary files.

### /usr
	subdivided list of non-essential files and commands

#### /user/bin
	lots of non-essential binaries, such as header files, shared libraries, own software, system management commands (admin)
	
#### /usr/share
	things common to multiple systems.

### /var
#### /var/log
	where the logs are stored