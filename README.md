# Makefiles

Sample Makefiles for GNU `make`, readily to be used for projects.


## Usage

	git submodule add https://github.com/hilbix/Makefiles.git
	ln -s Makefiles/Makefile.c.single Makefile
	make

Note:

- This needs a system capable of softlinks
- On Windows use WSL


## Update

	cd Makefiles
	git checkout master
	git pull
	cd ..
	make clean love


## FAQ

WTF why?

- Because I already have written zillion versions of nearly the same Makefile over the decades
- This here bundles these for easy update and reuse in future to make my life easier
- Probably I will add other common stuff here, too

`make love`?

- Why not?
- `make all` still works but should be reserved to some God.  I am not

`git submodule`s suck!

- Everything else like Gradle, Bower, Composer, NPM-Registry, DockerHub etc., usually sucks more badly than the black hole in the center of our galaxy
- `git submodule`s are the Holy Grail of ease
- If you already have `git`, there is no need to rely on something else to pull in external dependencies

Ideas? Questions? Fixes?

- Open Issue or PR on GitHUb
- Eventually I listen

License?

- This Works is placed under the terms of the Copyright Less License,  
  see file COPYRIGHT.CLL.  USE AT OWN RISK, ABSOLUTELY NO WARRANTY.
- Read: Free as free beer, free speech and free baby.  There must not be any Copyright on a baby.  Ever!
 
