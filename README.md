# ISplg-Compiler
- Compile your .ISplg Plugins using the documentation below. These plugins are used for the (NISZSE).

# Download The Compiler:
- Download [Here](https://github.com/Cracko298/ISplg-Compiler/blob/main/ISplg-Compiler.exe?raw=true).
- Create a file named ***source.txt*** in the same directory as the compiler.
- Then open it and look at the [Documentation](https://github.com/Cracko298/ISplg-Compiler#making-your-plugin) or the Provided [Example](https://github.com/Cracko298/ISplg-Compiler/blob/main/README.md#source-file-example).
- Need Help with Save-Data? We got you covered with this [Repo](https://github.com/ISZ-Hacker-Group/Ice-Station-Z-Save-Editing).


# Making Your Plugin:

> *Adding a Creator Name.
>> Creator = Cracko
>
> *Adding a Plugin Mode.
>> Load_Files = 1
>
> *Go-To Byte #.
>> Seek_File_1 = 32
>
> *Edit Found Byte.
>> Edit_Byte_1 = 9999
>
> *Developer Note.
>> Develop_Notes = Edits Save-Data Health To 9999.

# "Source File" Example:
```
Creator = Cracko
Load_Files = 2   # Can be from value "one" to a value of "three". "three" allows you to seek and edit data a total of "three" times.
Seek_File_1 = 32
Edit_Byte_1 = 9999
Seek_File_2 = 36
Edit_Byte_2 = 9999
Developer_Notes = This Plugin Edits your Health & Food/Hunger.
```

# Loading More Edits:
- ***Load_Files = 3 is the max value accepted.***

```
Load_Files = 3 >>> Edit_Byte_3 & Seek_File_3
```
```
Load_Files = 2 >>> Edit_Byte_2 & Seek_File_2
```
```
Load_Files = 1 >>> Edit_Byte_1 & Seek_File_1
```

# Output:
- ***This is the output of Compiler. Used the .ISplg from [Here](https://github.com/Cracko298/ISplg-Compiler/blob/main/README.md#source-file-example).***
```
Penpxb
2   # Pna or sebz inyhr "bar" gb n inyhr bs "guerr". "guerr" nyybjf lbh gb frrx naq rqvg qngn n gbgny bs "guerr" gvzrf.
32
20031
68
30031
Qrirybcre_Abgrf = Guvf Cyhtva Rqvgf lbhe Urnygu & Sbbq/Uhatre.
```

# Example Downloads:
- Edit Health [Download]().
- Get Flamethrower [Download]().
- Fix OpenByte Error [Download]()
- Get Hacked Clothes [Download]()
