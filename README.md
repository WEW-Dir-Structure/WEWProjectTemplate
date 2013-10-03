Wewmedia Basic project structure
=========
To Read: 
    http://en.wikipedia.org/wiki/Unix_filesystem
    http://babbage.cs.qc.edu/courses/cs701/Handouts/man_pages.html

- bin/ is where your script belongs
- share/dict is where dictionaries and Language related files belongs
- share/man/man1 is where you should write man explaining the basic options to run your scripts
  and/or executable
- src/ Is where you put your own C / C++ / Java code, you must define your own structure, clean
  after yourself, group things that belongs together in different dir, and write a corresponding
  Makefile.am for it.
- 
