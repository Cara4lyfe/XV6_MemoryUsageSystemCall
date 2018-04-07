PA3 - Part 2 - README 

Paolo Ratti Tamayo - A20352801
Jiateng Sun 	   - A20368601

This folder contains the following files:

	- myMemoryManual.docx, includes the manual for the myMemory() system call, and a 		description about the implementation of myMemory().

	- myMemoryTestcases.docx, includes screenshots of the results of the multiple test case
 	used to test myMemory() and explanations for each test case.

	- MITxv6/sysproc.c, is the MITxv6 file where myMemory() is implemented.

	- MITxv6/myMemoryTest.c, is the test file used for testing the correct functionality of 	myMemory() after various memory allocations and deallocations.


To run xv6, you need to have installed vagrant 2.0.2, and virtualbox 5.2.6 (because this two versions work with each other). Any older vagrant and virtualbox will also work, as long as the two are compatible with each other.

In the terminal, move into the 'MITxv6' directory, and  run the command 'vagrant up', to initialize vagrant.  

Next, enter the vagrant secure shell by running the command 'vagrant ssh'. 

In the vagrant ssh, change directories to /vagrant/ with 'cd /vagrant/'. Here, run 'make clean ; make' to compile xv6, and finally run 'make qemu-nox' to run xv6.

Inside xv6, you can type the command 'ls' to see the list of runnable process in xv6. The very last one, 'myMemoryTest' is our test program. 

myMemoryTest is a program that takes in an integer (from 1 to 8) as an argument, and executes the corresponding test case. 
