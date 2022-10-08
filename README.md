# GM-FilePicker
 Android GameMaker extension that can call OPEN_DOCUMENT Intent to allow user pick specific file (by default it's .zip archives)
I created it because of myself was lacking this kind of functionality on mobile builds. It's simple, but does its work.

# About
 Basically what it does it creates a new OPEN_DOCUMENT Intent, that shows up like a choose file dialog, where user can proceed to any .zip (can be changed) file, which is going to be asynchronously copied by the extension to the location that's accessible by GameMaker.
 * Everything is restricted by boundaries of `/data/data/packagename/files/` 
 * Intended to work on all devices with sdk 19 and newer.

It's unlikely to be updated. To see how it works, view example object.
