# Bypass GetModuleBaseAddress and GetExportAddress in C#
A proof of concept of real and native custom GetProcAddress and GetModuleBaseAddress in C#.

This took me so long time to code and find resources about it (mostly old and not working anymore or C++). I decided to write that in C# because I've never seen REAL implementation of that and I learnt so many things about low-level with windows from my own errors and test to other's code. Also most of native imports I wrote come from ReactOS code I translated to C# and then tested with ProcessHacker for PEB and Detect It Easy for Image structures.
<br>
Works with x86 and x64.
