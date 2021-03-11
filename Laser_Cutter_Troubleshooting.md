---
sort: 3
---

# Laser Cutter Troubleshooting

## Tips for importing vectors

### You must prepare you file for Laser Cut to properly import your vectors

- Laser Cut does not recognize fill. It only recognizes black or other colored vectors with a line weight of 1/2 pt or less.
- Text is not recognized either. In Adobe Illustrator, right click text and select 'create outlines' and then swap your fill and outline colors.
- Any object depending on line weight must be expanded so that a vector encloses the object.

## Laser Cut Software

### Laser Cut crashes or doesn't recognize my file when I try to import it

- Refer to tips for importing vectors above.

### The text in my file doesn't import

- Laser Cut doesn't recognize most text. In Illustrator you can right click your text and create outlines then make your outlines black.

### LaserCut does not upload my job to laser

- Save your job, turn off laser, quit LaserCut, turn on laser and then restart LaserCut.

### Error: Contour doesn't work, Soft Stop

- Check that the origin is within the bounds of the LaserCut art board (numbered grid).
- Check that no vectors lie outside the bounds of the LaserCut art board. Zoom way out to inspect regions far from the art board.

### Error: Laser does not run file

- The file artwork needs to fit on the Laser Cut Art board. Also make sure that imported DXF files are all placed on the Art board.

### Error: When downloading file to machine, LaserCut posts an alert that the driver is bad

- The large laser does not accept any cut speed slower than 5. If you set a slower cut speed, during download the software kicks an unspecified communication error. Set a speed 5 or greater and download again.

## Laser Operation

### When setting datum the platform rises but doesn't stop

- This is almost always because datum was hit when the laser nozzle was at the edge of the platform and the plunger was not over your material so it didn't not know when to stop.
  - Do not turn the laser back on before manually lowering the platform. To do this open the front access door with a key (there's usually a key left in one of the access doors).
    - 
    - For the small laser: Manually pull the belt to spin the lead screws clock-wise until the nozzle can safely move above the platform.
For the large laser: Manually pull the 2 belts to spin the lead screws clock-wise until the nozzle can safely move above the platform. Try to move each side the same amount to keep the bed level. Using a spacer adjust one side so the nozzle brushes (with the machine off) the spacer when it's sitting on the platform. Repeat on the other side of the platform to level. Ask for help if you're unclear with this procedure.
Always set Z datum over the middle of your material.
Check that the honeycomb tray is clear of the rim. Beware: the tray can get caught under the rim and cause havoc.
If head assembly abuts material support frame (the wire mesh thing), you need to lower the bed manually. To do so pull on the pulley adjustment belts in the bottom cabinet.
Email us if this happens because the platform may need to be leveled. contact@nordeastmakers.com

It sounds like the laser is hitting something and is loosing position running a job[edit]
This is caused by an unknown glitch and tends to happen on fast cuts.
Try importing your file as an .ai (Illustrator file) rather than a .dxf. For Laser Cut to recognize an .ai it must be saved as an Illustrator 10 file with file compression unchecked. You also need to have black outlines.
If that doesn't work try redrawing your lines in a CAD program other than originally. If they're simple vectors draw them in Laser Cut and delete the defective ones.

The laser is not firing when running my file[edit]
Make sure the exhaust fan and chiller are on.
Make sure your power setting is high enough to mark or cut material as needed.
The door must be closed!

The laser is not cutting through my material at settings that used to work[edit]
It's likely the lens and mirrors need cleaning. If you're not familiar with this process ask for help or contact us at contact@nordeastmakers.com

Large laser exhaust fan does not clear dust and smoke[edit]
Check the fan filter, it may be dirty. The fan filter is in the wood housing along the wall at the back left corner of the machine. Open the window latch on the housing, pull the filter down and out, clean it with running water, replace in housing.
