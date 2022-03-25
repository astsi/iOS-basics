# Debbugging in Swift:

## Breakpoints

-  Used to stop the program execution at the specified point.
-  Allows you to explore the details about the variables (current values,etc.) at the moment of the break.
- Simple breakpoints: 
    * place a breakpoint somewhere in the code
    * run the code
    * hoover over the used variables to see their current value/read it from the debug bar 
- Click on the Breakpoint navigator button to explore various kinds of breakpoints
- Sharing breakpoints with other developers - exists as an option 

## Swift Error Breakpoint

- Used to identify the root of the problem
- HOW? 

## LLDB - Low Level Debugging

### LLDB - po

- Can be used to observe the proprerties of a specified object (i.e. po swDev - prints out: ID: 1, name: "John", age: 25)
- Can be used to execute code such as comparations (i.e. po swDev.age < 30 - prints out: true)

### LLDB - p

- testing the scenarios what would happen if the object property had a value of x (i.e. po swDev.id = 68, some f-on prints out that he is too old to be working)

### LLDB - v

- you are able to use the name of the protocol to print out the property of a struct/class that inherrits that protocol (i.e. v employee - prints out: "John")
- you can't use it to execute code like po
  
## Network Link Conditioner

- Simulating the Network in Edge cases - you can use it to test how your program will behave when the bandwidth is 3G/100% lost/WiFi etc.
- Install the Network link conditioner in order to use this tool (found in additional tools for Xcode)
- You can use it in the simulator/device as well

## Looking into device's container
  
 - the way you can use to verify if the some data has been added to the database/container correctly/if the cashing has been done correctly etc.
 - download the container, check the data inside it

## Debugging issue which do not occcur on simulator, debug mode

 - creating a log file to determine what went wrong

## Debugging View Hierarchy

- --
### Useful resources:

https://developer.apple.com/library/archive/documentation/DeveloperTools/Conceptual/debugging_with_xcode/chapters/debugging_tools.html

https://www.youtube.com/watch?v=ipuxycB1ewY&t=300s

https://ohshitgit.com
