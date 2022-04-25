# RimNames
Repo for people to add custom Rim names that show up as NULL in game

So thanks to @ItzKaizen#1769 pointing out a very interesting feature I didn't know about. It's possible to name your `NULL` rims

Lets say for example, we use JDM rims from `https://www.gta5-mods.com/vehicles/jdm-rims-pack` after its been converted to work with FiveM of course

Inside the `x64/data/lang` folder inside the provided .rpf file is a list of wheel hashkeys and their given names.

Converting this: 
```lua
0x04A41A26 = Enkei RS05rr
```
into this:
```lua
AddTextEntry('0x04A41A26', 'Enkei RS05rr')
```
We can build a list of hashkeys with this names that your server will understand and use.

**I highly encourage others to add to this**

I think using a similar method, you can name cosmetics on custom vehicles..
