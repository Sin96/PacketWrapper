PacketWrapper 
===========
This is the official continuation of PacketWrapper by dmulloy2. The original version can be found [here](https://github.com/aadnk/PacketWrapper).

When reading and writing packets in ProtocolLib, it is necessary to know the order at which the fields are stored in memory. 
This requires you to decompile the Minecraft source code with [JD Gui](http://java.decompiler.free.fr/?q=jdgui), while decoding the meaning of a field by looking up an online [wiki](http://www.wiki.vg/Protocol) resource 
([tutorial](http://forums.bukkit.org/threads/lib-1-4-6-protocollib-2-0-0-safely-and-easily-modify-sent-and-recieved-packets.101035/page-2#post-1366140)). 
It would be much easier if these packets could be accessed as any other normal Java bean. 

Enter PacketWrapper. It contains wrapper classes for all known packets in 1.8, providing you with access to the fields by name, along
with automatic conversion to existing Bukkit enumerations and classes. It also includes a number of custom enumerations when appropriate.

You can use PacketWrapper as a dependency if you wish, though the intent is for plugin authors to simply copy-and-paste the classes they need into their 
project. 

Resources
--------
* [Downloads](http://ci.shadowvolt.com/job/PacketWrapper/)
* [ProtocolLib](http://www.spigotmc.org/resources/protocollib.1997/)

Building
--------
You can compile this project yourself by using the latest version of Maven.


Remarks
--------
This project was mostly generated by a [script](https://github.com/aadnk/Wrappit). 