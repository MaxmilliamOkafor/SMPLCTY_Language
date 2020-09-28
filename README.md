PROJECT GOAL!!
The aim of the program is to have source code that’s its easier for new programmers to grasp, by being like every day English when read aloud. Simplicity is interpreted language that uses a declarative paradigm. 


////////////////////////////////////////////
////////                        ////////////
////////  EXTRACT THE ZIP FILE  ////////////
////////                        ////////////
////////////////////////////////////////////

# SMPLCTY_Language
--- Created my own object-oriented programming language that uses the computation model based on the Turing machine ---

// LANGUAGE WAS CREATED WITH ECLIPSE //
// RUNS WITH COMMAND PROMPT //


SIMPLICITY (SMPLCTY)

README folder for running the example
Simple interpreter from Interpreters lecture, which did not need to be compiled as you could run straight.
1) In order to run the example programs written Simplicity
 open the command line-> change the directory to same folder as 
the README.docs file is found -> write "runTests" in the command, to see what each
 of the test scripts in the /example folder




/// TO BUILD ////

1)extract project from zip file to your chosen file location
2) open the command line then cd into the simplicity language folder 
3) check if runTest.bat file is not empty (if it is there must be some type of corruption happening; try re-downloading the project)
4) run the "runTest.bat" file > this will results corresponding to each of the example code provided
======create new test file==============
1) create a file with simplicity extentions in the example folder
2) to create an editional test edit the "runTest.bat" file  to include:-
 -java -classpath ./bin Sili < examples/<file name>.simplicity
3) so the code results of the new file actually print add to the "runTest"  :
  echo "=== Test14.sil ==="
 java -classpath ./bin Sili < example/test14.sil
========optional========
1) to check the output bat file matches with the code, cd into the examples folder where your will find a bunch of files 
with the ".simplicity" extension . these are where the code is interpreted from .
