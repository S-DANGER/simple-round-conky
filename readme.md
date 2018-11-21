(based on Tiscin's Conky : https://github.com/Tiscin/Rings-Conky)

A simple, small, but stylish Conky; with visibility on my :
- CPU, and its four cores
- RAM and SWAP usage
- /boot, /, and /home usage
- wired & wifi interfaces usage, and IP adresses

Three modifications on Tiscin's config :
- three levels : normal, warning & critical; with custom coloring of ring foreground when value is above a certain percentage
- overflow prevention : ring foreground will not exceed the max value of ring background (useful when value is NOT a percentage)
- easily customizable : colors, alphas & level limits are variables, written at the beginning of conky_dashboard.lua
  (font color also has to be modified inside .conkyrc)

These files should work on any config, with a minimum of tinkering.
(except for network interfaces names,
        if you have more/less than 3 partitions/filesystems,
        if you have more/less than 4 cores,
     or if you don't have a swap)
