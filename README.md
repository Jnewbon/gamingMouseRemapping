# Remapping mouse side buttons

This Repo addresses the mapping issue some mice have with the side buttons. 
For example Razer Naga Chroma has 12 button on the side of the mouse, these are by default mapped to the keys 1,2,3....9,0,-,= on the main keyboard.

In MMOs however this keymapping is undesirable and remapping them to the numpad is the desired option.

# Installation

Copy the require mapping file to your home directory
source the file in your .bashrc
This does require that you open a terminal to apply the remapping

```
cp .RemapRazerNagaChroma ~
nano .bashrc
```
Add the following line
```
source .keyRemappingNaga
```
