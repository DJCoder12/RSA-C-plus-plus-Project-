Donovan James
CPS 222 Project 1

Files Submitted:
ReallyLongInt.cc/h- This program creates a really long int class that uses an array to handle integers outside of the boundaries of standard c++ data types. This can be compiled using the command g++ -o ReallyLongInt.exe ReallyLongInt.cc


factorial.cc- This program generates the factorial of a ReallyLongInt. This can be compiled using the command g++ -o factorial factorial.cc

numberTheory.h/cc- This program supplies methods used in both keygen, encrypt and decrypt. This can be compiled through the use of make numberTheory.o

keygen.cc- keygen is a program that generates keys for both the public and the private keys. This can be compiled using the make file

encrypt.cc- This program reads a file of text and uses the public key generated to hide a message. This can be compiled through the use of the make file make all command. 

decrypt.cc- This program reads an encrypted file and uses the private key generated to hid a message. This can be compiled through the use of the make file make all command.

Makefile- This is my make file. It contains a series of commands for compiling my code correctly.
readme.txt
cover sheet

Known issues :

. My encrypt enters a never ending loop despite not entering the only while loop in the file.

. My decrypt has a similar issue of entering a never ending loop.
