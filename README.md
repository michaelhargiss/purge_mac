# purge_mac

Free up that RAM!

### Problem
At the end of a day of school and work, unecessary processes hog my Mac's RAM. I want to kill those extraneous processes without killing the ones I'm actually using and without having to reboot.

I can open Terminal and enter `purge`. Nice, but inconvenient, particularly when I'm running low on memory as it is.

### Solution
*_purge_mac_* uses the `purge` command to accomplish the same thing, without having to open Terminal.

### How do I use it?

Download the script and keep it somewhere accessible, such as your desktop. When you want to free up RAM without killing the processes you're actually using, just double-click the file. 

Your machine will appear to freeze momentarily. This is temporary and normal. Just give it about ten seconds and you'll be back in business.

### Dependencies?

You just need a Mac with Applescript installed.

### Notes

Here's the actual script:

```Applescript
do shell script 'purge'
```

I use [Alfred](http://www.alfredapp.com/) to quickly execute this script.
