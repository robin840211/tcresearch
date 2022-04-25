# Thaumcraft 4.x-5.x Research Helper

Link: 
[Thaumcraft Research Helper](http://robin840211.github.io/tcresearch/)

## Usage for Helper page
1. Choose  **`From`** and **`To`** Aspects from your research note
2. Choose **`Min. Steps`** which means minimum number of steps between those aspects.
3. Click  **`Find Connection`** so the script will search for the shortest path that connects the two aspects (well, with at least the minimum length it should be).

## Note
Sometimes the length of any path is longer then the given minimum, but this should not be a problem for your research note.

## Mods aspects helper compatibility
Currently support only Forbidden Magic, Magic Bees, Gregtech, which appends correspond aspects in list.
You can enable/disable specific aspects quickly by the Addons checkbox if you need.

## Disabling aspects
If your are unhappy with the path you got, because you do not have access to those aspects yet or they are quite rare, 
simply disable those aspects from Available Aspects:. The script will then try to find paths without these. Note that 
this may cause the path to grow longer. If too many aspects are disabled and there are no paths left without any of 
those, the script will try to find the shortest path using the minimal number of disabled aspects.

## Description for Helper Page
This script helps you with your Thaumcraft 4.x-5.x research. If you have a research note with two aspects that you don't 
know how to connect, simply choose them in the dropdown list above (From: and To:). Additionally, choose the minimum 
number of steps between those two aspects. If in your research note, the two aspects have two blank spaces between 
them, choose the value 2 for Min. Steps. Then click Find Connection and the script will search for the shortest path 
(well, with at least the minimum length) that connects the two aspects. Note that sometimes the length of any path is 
longer then the given minimum, but this should not be a problem for your research note.

If you are unhappy with the path you got, because you do not have access to those aspects yet or they are quite rare, 
simply disable those aspects from Available Aspects:. The script will then try to find paths without these. Note that 
this may cause the path to grow longer. If too many aspects are disabled and there are no paths left without any of 
those, the script will try to find the shortest path using the minimal number of disabled aspects.

## License & Source
This work is licensed under a [Creative Commons Attribution 4.0 License](https://creativecommons.org/licenses/by/4.0/).
Sources can be found in the [github repository](https://github.com/robin840211/tcresearch).

This work is originally from [ythri version's Github Page](https://github.com/ythri/tcresearch),
with forked from [ralileo16's Github Page](https://github.com/ralileo16/tcresearch) which update few stuffs.
