# RMLemulator
A simple Register Machine Language "emulator" written in C++ for Windows/CentOS for CPSC 3740 at the University of Lethbridge.

## Getting Started
1. Clone the repository
```
git clone https://github.com/pretenzo/RMLemulator
```
2. Browse to the cloned directory, and open the executable:
### Windows (from Command Prompt)
1. Browse to the cloned directory:

```
cd mydirectory\RMLemulator\exe\
```
2. Run the executable.
```
RMLemulator_win64.exe
```

SmartScreen might say that it protected your computer from an unsigned piece of code - just click "More info" and then "Run" and the program will execute.

### Linux (CentOS - for lab computers)
1. Browse to the cloned directory:
```
cd mydirectory\RMLemulator\exe\
```
2. Run the executable.
```
./RMLemulator_centos
```

## Using the emulator
The emulator accepts a text file - give it the full location of the file with properly coded instructions and it will interpret and run the RML code:

i.e.
```
Register Machine Language Emulator v1.0
(c) 2020 Lorenzo Conrad (XXXXXXXX).

Please enter a filename to open: C:\Users\Example\ADD.txt
```
