# RaspberryPi_OS
Using https://wiki.osdev.org/Raspberry_Pi_Bare_Bones as a jumping-off point, as well as https://www.cs.bham.ac.uk/~exr/lectures/opsys/10_11/lectures/os-dev.pdf as a guide. Also huge shoutout to Jsandler18 https://jsandler18.github.io/ for making a handy tutorial 
*Note for anyone using this repo to do their own project: I will be using a Raspberry Pi 3, while this tutorial uses a 2. There are a few big differences.*

## Goal: Practice with Kernel writing and board bringup for Raspberry Pi 3 board. 

Project Outline:
### Step 1: Sign of Life ✔️
  Get something to display in the terminal (i.e. start up the board, make it output something)

### Step 2: Set up the full OSDev Directory (here) 
  2.1: Use JSandler18's tutorial + https://www.youtube.com/watch?v=FkrpUaGThTQ to set up directory
  2.2: What kind of OS am I building? --> Design choices?
      *I want to see what decision decisions go into making a Realtime OS (RTOS), but maybe I'll just play around with FreeRTOS and an Arduino outside of this.*

### Step 3 (most of the work): Actually making the thing work -->
Dynamic Memory Allocation
PCB management and interrupts
Concurrency (?) --> if time, this one isn't necessary for Step 4 but it's nice not to waste hardware.

### Step 4: Load this onto Hardware (we're not in QEMU anymore) and do something
I'm going to hope that this bit works: https://jsandler18.github.io/extra/hardware.html

### Step 5: Something cool??
  
