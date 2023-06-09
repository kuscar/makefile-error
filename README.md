# Makefile
Makefile for running tests on Apple MacBook

## Problem: 
  - The Makefile for the subject Programiranje2 at the Faculty of Computer and Information Science (University of Ljubljana) does not work on Apple MacBooks.

## Requirements:
  - Homebrew
  - run 'brew install coreutils' in your terminal
 
## Solution
There are two known possible errors:
   1. Error: Timeout
       - Remove "--ignore-trailing-space" from the Makefile or
       - Copy the contents of Makefili/osnovni/Makefile.
   2. Error: Timeout and illegal character N
       - Copy the contents of Makefili/ce-se-vedno-ne-dela/Makefile.
 
