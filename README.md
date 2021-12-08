# USB-Drop

## What is it?

When you want to perform a USB drop test during a physical penetration assessment, but the client doesn't want you to use any malicious devices like a Bad_USB.

Simply use the macro on a enticing looking file, such as Payroll.

## What happens when it's opened?

1. It'll attempt to gain a few basic details from the host system, Username, Time & Date and Serial Number, then store them in a global variable. 
2. A appear, which will read the "Info.txt" file and display it as a message box
3. The system information previously gathered will be stored into a text file
4. Should a HTTP server be setup and the IP:Port details are correct, it'll send the system information to that server as a form of remote log
