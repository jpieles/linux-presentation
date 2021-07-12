# INTRODUCTION
*> Richard Stallman Video*
GNU Linux became thr most used
operating system and is the
largest community software project
ever worked on.
Today I want to show you, how that happened,                           
how the system works and why I think
that it's better than the rest.                                                                  

First I will go into how all started
with the history and the GNU Linux Philosophy.
To explain how it works I will show how it
is built, what special types of software there are
how the system and everything around it is developed
and the from that resulting distributions

After that, I cover the advantages of GNU Linux
or why it is best for me.

And in the end I will give a short summary about
what I talked about.

# HISTORY
The Story begins at Bell Labs, the research department
of AT/T in about 1969.
When these two guys, Ken Thompson and Dennis Ritchie
started to develop their new operating system UNIX.
Dennis Ritchie later developed the C Programming Language
to rewrite the UNIX source code.
Unix was a great success, and was widely used in
computers of universities.
AT/T was under control of the USA and could not
sell software, so unix was distributed for free.
In 1981 AT/T lost its monopoly and was able to
sell UNIX as UNIX System III.
In all the years unix was free universities changed
it up for their own need, i.E. the
Berkely Software Distribution (BSD).
So the IEEE introduced the "portable operating system
interface" POSIX.

Many passionate UNIX users were not pleased by
the new UNIX licensing.
One of them worked at the Artificial Intelligence
Department at MIT in 1983.
It was Richard Stallman, the guy in the video in the beginning.
He founded the GNU Project, which stands for GNU is not UNIX.
His idea was to create a unix like operating system made
of completely free software.
He came far, but the main part of the operating system was missing.
The Kernel.
In 1991, a finish student, called Linus Torvalds wanted to
create a terminal system. To have access to his university
computer from his home computer.
But what he has written became more and more a full
unix operating system kernel.
So he wrote an email, that started everything.

So the end of the story is that Linux became the GNU
Kernel and the operating system GNU Linux was born.
 
There is actually an offical GNU Kernel, GNU Hurd in
development, but after 40 years of development it's
only version 0.9 ... so yeah.

# PHILOSOPHY
The Unix philosophy is pretty simple.
Everthing is a file, really everything.
Files, Programs, Directories (Folders), even Devices
like the CPU or the keyboard. Everything is a file.

And it becomes more specific, because everything is
a text file aswell.
This is quite powerful because the inputs and outputs
of programs is text. You can use the output of one program
as the input of the next program.

And the 3rd and most important is.
There aren't big programs but
small programs which provide only on task.
And for greater funcionality you can bind them together

The GNU Philosophy
GNU is all about freedom.
freedom for the user.
Stallman said.
Either the user controls the software
or the software controls the user.
Because proprietary software let's
you only do and see what the developers allow you to.
Free software is defined by the 4 freedoms.

Freedom 0
The freedom to run the program for any purpose.
for example lo licenses for only one device.

Freedom 1
The Freedom to study and change the program
also the acces to the underlying source code
also known as open source.
The source code is open for everyone and you can
change it to your own needs.

Freedom 2
The Freedom to share copies to help your neighbor
Like you would share a recipy.

Freedom 3
The Freedom to distribute copies of modified versions
to others. You can change the program and share
copies of that as well

All of that is defined in the GNU General Public License
GPL. If a software stands under the GPL, all copies
and modified versions must have the GLP as well.

# ARCHITECTURE
GNU is a modular system. Every gnu system
can be different based on what you need.






What you see here is a simplified view on the architecture.

At the Bottom is the hardware,
on top of that is the Linux Kernel, or just Linux with
the device drivers to communicate to the hardware.
But Linux is only a part of the GNU System.

So what we call Linux is actually just GNU.
As a user you don't see anything from the Kernel.

On top of everything are the applications the user
uses.

Nearly every computer hardware can be used to run Linux
on it.
starting with desktop computers, what was the initial
task of Linux, over to small arm based systems like
smartphone or the raspberry pi.
Servers and Mainframes.
Network gear and embedded systems like ATM's or vending machines
Even Devices which aren't designed for Linux can run it.

And the ISS uses a Linux Operating system.

The Kernel is the main part of the operating system.
It contains the device drivers which is software
for a specific type of hardware (like peripherals)
The main task is scheduling and managing hardware resources.
It has to manage hundreds of applications running simultaniously,
and manage the memory and cpu cores.

It's needed to run a computer on a more abstract way.
Use multiple applications and switch between them.

The GNU system is the part, that we as users see from the
operating system.
It handles the configurations of the programs we use.
Handles user accounts and can even handle multiple users 
at once.
It provides basic tools, like texteditors, the shell, compilers, etc.
And contains libraries needed by applications and developers.

# SOFTWARE
For me Linux is defined by a set of software

A very helpful one is the package manager
It was initially implemented in 1994 in Debian GNU Linux
and is nothing other than a app store.
There are several package managers.
The most common are apt and pacman.
You can search, install, deinstall and manage programs.
You can easily find which software is installed on you system
and update it automatically.

The Terminal is the most used part in Linux.
Everything can be down within it, but faster.

One optional component is the X Window System
it provices basic functions for input from mouse and
keyboard and output via a monitor or speaker.
It can be used to draw shapes and text etc.

The Desktop Environment is used to have a graphical user interface
It uses the X Server. A Desktop Environent consists of 
a window manager, which defines the appearance, and the workflow.
Like having multiple workspaces. How Windows are arranged etc.

A Desktop Environment also brings utilities for power management,
brightness control, network managmement
and basic tools like editors and a file manager.

It is also possible to only install a Window Manager.

Examples for Desktop Environment are Gnome.
Which is used on the school machines.

KDE which is the the one with the most tools, and is
also highly customizable

XFCE which tries to be lightweight and can also
be customized completely.

And there are also tiled Window managers which are my favorite

If you are interested in Desktop Environments designs
check out the subreddit unixporn.
There are people showing how sick their environments look like

One downside of Linux is that Software from Microsoft
and Adobe isn't compatible.
But there is an alternative for nearly everthing.
The best examples are libreoffice for microsoft office.
Gimp for Photoshop and co.
And kdenlive which is an alternative for all video editing software.

But the most applications also run on Linux or
have its origin in Linux 

# DEVELOPMENT
Changes for the Linux Kernel are braked down to
so called patches. A patch can implement a new feature,
fix a bug, improve performance and so on.
If the patch is ready it is send into a mailing list
depending on what type of patch it was.
There it's discussed, if it even makes sense to
implement it.
If its ready there, the developer sends the patch to
a senior linux kernel developer, who is the maintainer
of 1 or more of the hundreds of parts of linux.
If it's ok for him, it's send to our Benevolent Dictator
for life Linux Torvalds who has the ultimate authority of
what comes into the new kernel and what doesn't.

https://github.com/vim/vim

# DISTRIBUTIONS
A Distribution is a set of tuned software.
Consisting of a Linux Kernel, GNU Software
and preinstalled applications.

Most distributions only differ in the package manager
and the preinstall Desktop Environment.

There are hundreds of distributions, but I will only show
a few.

Most distributions are based on another distribution.
Most are based on these.

The currently most used are debian and archlinux.
They are both minimalistic and stable.
They have the best package support.

RedHat is for businesses only, but they also have
fedora which is accessible for everyone.

All of them are more used in business environments.

If your new to Linux i would recommend one of those.
Manjaro is based on archlinux but it's easier to install
and most configuration is done for you.

Ubuntu is based on Debian and is
the most popular Linux Distribution, because
it was the first, which was usable for normal users.
You could finally install and use it, without having
to be a computer scientist or something.

Linux Mint and Pop OS are based on ubuntu.
pop os is cool because there developers
system76 are also building computers designed to
run with linux. pre installed with pop os.

There are also special distributions.
KALI is designed for cyber security.
With gentoo you have to compile everything for yourself

Parabola is Archlinux with only free software
Trisquel is Ubuntu with only free software
(used by Richard Stallman)

I use Arch btw 

# ADVANTAGES
Linux is more secure.
One reason is that less people use it and so there is
less malware.
And another reason is that it's open source and
security holes can be found quickly

In Linux you have more privacy than with other operating
systems.
With other operating system you don't even know if
you have privacy because you cannot now, what the
system does in the background and what data is send.

Linux is more reliable. It has fewer bugs than other
systems and can run for years without a restart.

modularity and customizability are for me the best advantages.
A Linux System can be built differently and can
contain only the components you need.
For example you mostly don't need a graphical user interface
for a server.
Linux is 100% customizable.
a lot things can be customized with configuration files
and if that isnt enough you can always change the source code
if needed

Linux is lightweight, perfectly optimised and has
the best performance.
Old computers which are too weak for a modern windows
can be easily resurrected with an Linux install.
Hardware can also be used longer, because Linux
is very resource efficient.

With package managers you can easily install, remove
and update software.
The software comes from reliable sources and
can be updated all at once.

Everything can be done within the terminal.
Even image manipulation and web surfing.
Most things are faster than done with a graphical interface
i.E. coping, moving files

theoretically speaking, everthing within the operating system
can be automated.
Most Desktop environments provide tools to create
makros for specific things, or to start programs
at startup on a specific workspace etc.
There is also time based automation with cron.
To repeat a specific task i.E. every wednesday, at 2AM

Linux is great for developers or it people in general.
Most tools needed are installed like compilers etc.
There is also a lot of server software.
tools for cyber security.
and many more.

And the greatest advantages are
its easy to use, if you find a suitable distribution
its free as in free beer as well as in freedom
It has a great community, there is always someone
who can help you out.

# SUMMARY

