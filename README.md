# Multi-threaded-Programs-and-Synchronization-in-C
Project for CS342 course - Operating Systems

CS342 PROJECT 2, SPRING 2019
---------------------------------------------------------------------------
PROJECT MADE BY:

NAISILA PUKA 21600336 SECTION 2
KUNDUZ EFRONOVA 21600469 SECTION 2
---------------------------------------------------------------------------

integer-count.c invokation is as specified in the hw.

---------------------------------------------------------------------------
Our test.c source file is tested through the following invokation example:
	
	./test.c N K T W

where for the value of N K T and W we use integers:

N stands for size of hashtable
K stands for number of locks (N has to be multiple of K)
T stands for number of threads
W stands for number of insertion operations performed per thread

below is example of invokation

	./test.c 100 5 10 150

Output will show the time spent to finish the operations in ms.
Read more in our report.
---------------------------------------------------------------------------
