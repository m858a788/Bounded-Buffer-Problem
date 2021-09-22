# Bounded-Buffer-Problem

Design a programming solution to “bounded-buffer problem using the producer-consumer processes” by using standard counting semaphores.
What we need: (both processes will share these resources)C
empty – standard counting semaphore
full –standard counting semaphore
mutex – mutex lock 

TO COMPILE: gcc -pthread project.c -o myProj

TO RUN:  
./myProj 20 5 5 
(the 20 is how long ur program will run before terminating
5 is the number of producer threads
other 5 is the number of consumer threads
