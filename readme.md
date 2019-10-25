
**ClarionLive Ultimate Debug Class**

Debug class to send messages to DebugView, available at http://technet.microsoft.com/en-us/sysinternals/bb896647  

**Code contributed by:**
     Mike Hanson
     Mark Goldberg
     John Hickey
     Skip Williams see http://www.clarionmag.com/cmag/v5/v5n01debuger.html
     Roberto Artigas
                                                                            
**Class Methods:**

     Debug(<string>) - Send any string to the debug window
     DebugQueue(<queue>,<string>) - Display the contents of a queue
     DebugEvent - Use to display events and additional useful information
     DebugClear - Clears the DebugView window  

**Class Properties**

     DebugOff - TRUE to turn debugging off, FALSE to turn debugging on
     DebugPrefix - Used to filter Debug messages, prepended to the Output String
     SaveToFile - if TRUE, will save debug messages to an ASCII file                           
     ASCIIFileName - name of ASCII file to save debug messages to, default is 'Debug.txt'