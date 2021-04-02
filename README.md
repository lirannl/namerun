# namerun
A small shell script which can run executables with a custom name.  
To use, invoke namerun with the name, and the command - for example:
```namerun interpreter python``` will create a python interpreter process named "interpreter" (meaning there will not be any process named "python").
```namerun hello python -c print("Hello, world!")``` will create a python process named "hello" which will print "Hello, world!" and exit.
