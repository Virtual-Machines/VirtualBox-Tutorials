# Tutorials VirtualBox

You can download the mp4 videos or read the steps:

**Import OVA VirtualBox**

How to import an OVA file on VirtualBox step by step. This is useful to work easily with virtual machines offered on this site
1. File -> Import Appliance (or Control + I)
2. Appliance to import dialog 
3. Click on upload button and select file
4. Selected file path is shown. Click Next
5. Settings
6. Importing...
7. You can run your imported machine with Start button


**NAT Port Forwarding VirtualBox**

How to access to a guest served website (or web service) from host through port forwarding technique on a NAT of VirtualBox.

This is very useful because it allows you to develop web applications in a Gnu/Linux virtual machine and test them on a Windows or Mac host using different browsers (Internet Explorer, Edge, Safari, Chrome, Opera...) unavailable on the penguin OS

1. Click Settings when a virtual machine is selected
2. Go to Network tab
3. Click on Advanced -> Port Forwarding button
4. Add a new rule using right green plus (+ icon)
5. Set host and guest ports (IP are optional and not needed on localhost) and click OK  button
6.  Serve a web application on guest using the port previously configured as "Guest Port". Example: python3 -m http.server 8080
7. Finally, enter on a host web browser using  "Host port" of localhost. Example: localhost:8080


**Shared Folders VirtualBox**

This functionality is useful when you need to transfer data between host and guest (and bidirectional clipboard is not enough)
All machines offered by me have VirtualBox Guest Additions installed with bidirectional clipboard configured and are compatible with Shared Folders. If you follow this tutorial on them... You are ready to enjoy it!
1. Click on Settings
2. Go to Shared Folders tab and click right green plus button
3. Select Folder Path on host using arrow or type it manually. 
4. Set Folder name. Check Auto-mount. Click OK.
5. Click OK
6. Click on Start to run your machine with a shared folder
