# -------------------------------------------------------------------------------------------------------------------------------------------------------- #

# NimForCsgo

# How do I get nim?

go to : nim-lang.org | download the 64 bit version of nim. | MAKE SURE YOU HAVE A WORKING NIM INSTALL

# What does this file do?

this file includes everything needed to make a dll to inject into csgo!

# How do I use this file?

first go to | https://mega.nz/file/fdVj1aKa#kHfa4y6XazSMjw1ohJJX8zJ_JwFE9pX_qxHWKWXDupg | and download the .zip

then  go to This PC -> Local Disk (C:) in the windows file explorer and paste both mingw32 and mingw64 into the c drive
after that go to wherever you installed nim and paste the config file into it, overwrite the existing file and boom! you should now be able
to compile 32 bit dlls to inject into csgo

# How do I compile my .nim file?

Good question, you open nim.exe then type:

`nim compile --NoMain --app:lib <path to file you want to compile here>` THIS COMPILES A 64 BIT DLL WHICH CANNOT BE INJECTED INTO CSGO!!!

`nim compile --NoMain --app:lib --cpu:i386 <path you want to compile here>` THIS COMPILES A 32 BIT DLL WHICH CAN BE INJECTED INTO CSGO!!!

# I get errors and don't know how to use google to fix them?

head over to: https://discord.gg/6zMyG2SmuW to get some coding help!

# -------------------------------------------------------------------------------------------------------------------------------------------------------- #
