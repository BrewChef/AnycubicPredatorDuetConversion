watch https://www.youtube.com/watch?v=BgkJVgFnPaE for first idea and have this opened or printed for reference https://duet3d.dozuki.com/Wiki/Duet_2_Maestro_Wiring_Diagram

- connect hotend, bed and their thermistors to the respective ports at the Duet (Bed and E0)
- maybe you've got to extend the hotend cable (I had)
- connect motors  X, Y, Z and E to the new board as usual, you can recrimp new connectors, but you don't have to (see video)
- connect the endstops of X, Y and Z to the respective ports on the Duet, but take care of the different pins by recrimping or using jumper cables 
- connect the filament runout sensor to the E0 endstop and the Level sensor to E1 endstop, same as above
- if you want to replace the hotend cooling fan by e.g. a noctua with 12V, than you have to add an extra wire to the cabling down to the effector
- maybe also one or more additional wires for a different level sensor?
