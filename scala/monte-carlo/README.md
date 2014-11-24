Scala Monte Carlo Examples
==========================


This code should work on any system with an internet connection and a recent version of Java installed. Make sure you have Java installed correctly before proceeding.

The code uses "sbt" (the simple build tool) as the build tool. The sbt launcher has been included in the repo for the benefit of those new to Scala. It should be possible to run sbt from this directory by typing:

..\sbt

on Windows (which should run "..\sbt.bat"), or

../sbt.sh

on Linux and similar systems. If you want to be able to experiment with Scala yourself, you should copy the script and the file "sbt-launch.jar" to the same directory somewhere in your path, but this isn't necessary to run these examples.

The sbt launcher script will download and run sbt, which will then download scala, the scala compiler, scala standard libraries and all dependencies needed to compile and run the code. All the downloaded files will be cached on your system for future use. Therefore, make sure you have a good internet connection and a bit of free disk space before running sbt for the first time.

Assuming you can run sbt, just typing "run" at the sbt prompt will compile and run the example code. Typing "console" will give a Scala REPL with a properly configured classpath including all dependencies. You can type scala expressions directly into the REPL just as you would in your favourite dynamic math/stat language. Type "help" at the sbt prompt for help on sbt. Type ":help" at the Scala REPL for help on the REPL.

sbt dependencies are specified in the file "build.sbt". The code itself is in the file "monte-carlo.scala". Read both these files carefully to understand how everything works.

When you are happy with this example, hop over the the "regression" directory for a slightly more complicated example.

Darren Wilkinson

November 2014


