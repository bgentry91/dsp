# Learn command line

Please follow and complete the free online [Command Line Crash Course
tutorial](https://web.archive.org/web/20160708171659/http://cli.learncodethehardway.org/book/) or [Codecademy's Learn the Command Line](https://www.codecademy.com/learn/learn-the-command-line). These are helpful tutorials. Each "chapter" focuses on a command. Type the commands you see in the _Do This_ section, and read the _You Learned This_ section. Move on to the next chapter. You should be able to go through these in a couple of hours.

---

### Q1.  Cheat Sheet of Commands  

Here's a list of items with which you should be familiar:  
* show current working directory path
* creating a directory
* deleting a directory
* creating a file using `touch` command
* deleting a file
* renaming a file
* listing hidden files
* copying a file from one directory to another

Make a cheat sheet for yourself: a list of at least **ten** commands and what they do.  (Use the 8 items above and add a couple of your own.)  

> >
> > pwd - show current working directory path
> > ls - show files & folders in current directory
> > cd .. - move up one directory
> > mkdir - creating a directory
> > cp - copy file
> > rm -r - deleting a directory
> > touch - creating a file using `touch` command
> > rm filename - deleting a file
> > mv filename newfilename - renaming a file
> > ls -a - listing hidden files
> > cp directory/file directory/ - copying a file from one directory to another
> > mv - move a file


---

### Q2.  List Files in Unix   

What do the following commands do:  
`ls`
`ls -a`  
`ls -l`  
`ls -lh`  
`ls -lah`  
`ls -t`  
`ls -Glp`  

> > 
> > `ls'       - show files and folders in current directory
> > `ls -a'	   - show all files and folders in current directory (including hidden)
> > `ls -l`    - show all files & folders in long format
> > `ls -lh`   - print readable file sizes
> > `ls -lah`  - show long format with readable file size
> > `ls -t`    - sort files by date & time
> > `ls -Glp`  - show long files, dont print group name, append '/' to directories


---

### Q3.  More List Files in Unix  

Explore these other [ls options](http://www.techonthenet.com/unix/basic/ls.php) and pick 5 of your favorites:

> >
> > '-g'	- display files by timestamp
> > '-m'	- displays names as comma separated list
> > '-x'	- displays files as rows across the screen
> > '-b'	- displays nonprinting characters in octal
> > '-R'	- displays subdirectories


---

### Q4.  Xargs   

What does `xargs` do? Give an example of how to use it.

> > It allows you to build & execute commands from standard input. Some commands only take input as arguments.
> > An example of this is using the find uility to retreive a long list of file names and trhen using xargs rm to remove all of those filenames.

 

