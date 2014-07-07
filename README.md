# purge_mac: free up some RAM

This is a simple script, but it's useful.  

# Problem
At the end of a day of school and work, unecessary processes hog my Mac's RAM. I got tired of rebooting in order to kill those processes and have a clean RAM slate. I wanted to kill those extraneous processes without killing the ones I was actually using.

I can open up a CLI shell (Terminal) and type [tt]purge[tt]. Nice, but inconvenient, particularly when I'm running low on memory as it is.

# Solution
This AppleScript uses the 'purge' command to accomplish the same thing, without having to open a shell window.

# How do I use it?

Download the script and keep it somewhere accessible, such as your desktop. When you want to free up RAM without killing the processes you're actually using, just double-click the file. 

Your machine will seem to freeze momentarily. This is temporary and normal. Just give it about ten seconds and you'll be back in business.

# Dependencies?

None. You just need a Mac.

# Notes

Here's the actual script:
[tt]do shell script 'purge'[tt]

I use [Alfred](http://www.alfredapp.com/) to quickly execute this script.