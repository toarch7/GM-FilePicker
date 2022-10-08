# GM-FilePicker
Android GameMaker extension that can call ACTION_OPEN_DOCUMENT Intent to allow user pick specific file (by default it's .zip archives).
I created this because of myself was lacking this kind of functionality on mobile builds. It's simple, but does its work.

# About
 Basically what it does it creates a new OPEN_DOCUMENT Intent, that shows up like a choose file dialog, where user can proceed to any .zip (can be changed) file, which is going to be asynchronously copied by the extension to the location that's accessible by GameMaker.
 * Everything is restricted by boundaries of `/data/data/packagename/files/` root directory.
 * Was made for GMS2 2022.9, though it doesn't matter that much because extension's Java part is the same even for GMS1.4 and you can easily use it there.
 * Intended to work on all devices with sdk 19 and newer.
 * I don't care about being credited.

It's unlikely to be updated. To see how it works, view example object.
