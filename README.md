CS456ASST2
==========
  ___ ___ _ _  ___   __     _   ___ ___ _____ ___ 
 / __/ __| | || __| / /    /_\ / __/ __|_   _|_  )
| (__\__ \_  _|__ \/ _ \  / _ \\__ \__ \ | |  / / 
 \___|___/ |_||___/\___/ /_/ \_\___/___/ |_| /___|
                                                  
- Version of Compiler:        GNU Make 3.81

- Test machines:			  [linux016, linux024, linux32].student.cs.uwaterloo.ca

- Program Intructions:
  1. Unzip the zip file and use "make" to compile code.
  2. Put everything(sender, receiver programs, nEmulator, file to send) in the same folder
  3. Open 3 terminals(Could be on different machine) and enter the program folder.
  4. Start the nEmulator first. 
     e.g. nEmulator <Forward nEmulator port #> <receiver address> <receiver port#> <Backward nEmulator port #> <sender address> <sender port#> <max delay> <drop rate> <verbose mode>
  5. Start the receiver.
     e.g. java receiver <nEmulator address> <Backward nEmulater port#> <receiver port #> <output file name>
  6. Start the sender.
     e.g. java sender <nEmulator address> <Forward nEmulater port#> <sender port#> <File name to send>
  7. Wait for a while then you should be able to see the result :)