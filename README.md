Wewmedia Basic project structure
=========
To Read: 
    
    http://en.wikipedia.org/wiki/Unix_filesystem
    http://babbage.cs.qc.edu/courses/cs701/Handouts/man_pages.html
    http://www.gnu.org/software/automake/manual/html_node/Subdirectories.html
    https://github.com/tessonec/PySPG/wiki/Makefile-python


    We are using autoconf and automake so you should only change Makefile.am file to get your
    project to be linked, compiled and installed wherever you wanted. Please read about howto 
    write proper Makefile... it's plenty of howto around for that.

- bin/ is where your script belongs. Don't forget to write proper Makefile.am for it.
- share/dict is where dictionaries and Language related files belongs.
- share/man/man1 is where you should write man explaining the basic options to run your scripts
  and or executable.
- share/docs is where you should put all related documentation files to your project (use case,
  project documentation, analysis, etc... ).
- src/ Is where you put your own C / C++ / Java code (code need compiling), you must define your own structure, clean
  after yourself, group things that belongs together in different dir, and write a corresponding
  Makefile.am for it.
- 
