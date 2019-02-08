To compile a new program, first place the name of your cpp file that contains main in the MAIN_CPP_FILES variable on line 29 of the makefile. The names of the two examples, CommandLineFinch.cpp and SampleMain.cpp, are already present - you can remove these if desired.

Next, if needed, add any other cpp files that are used by your program to the OTHER_CPP_FILES on line 30 of the makefile. 

Next, if needed, add any header files you're using to the HFILES variable on line 32. 

Run 'make all' from the FinchC++ directory to produce an executable for all the programs in MAIN_CPP_FILES to the exes folder in the FinchC++ folder.

Note for Windows: If you are running windows you need to either add the hidapi.dll and libstdc++-6.dll files to the directory you are running your executable from or copy the dlls to the Windows\System32 directory. 