2022 04 08

# Improving my anti-static precautions

In the past I have crocodile-clipped my anti-static wrist band to the fan-cage of my soldering station.  
The cage is screwed to the metal chassis and the flex looks like 3-core, so I assumed it must be well earthed.  

# Is the solder station a good place to clip my ESD strap?
## Pros
- I can see when it's connected
- is easily accessible
- conveniently sized to clip to
- gives a good electrical connection to the bare metal
- is hidden from sight behind the solder-station 
- offers an ok mechanical connection for the croc clip to grip
- uses an existing connection to earth

## Cons   
- there's stress on the clip (the wire orients straight up)
- I have to route the ESD wire around my work area
- I never tested if it's actually earthed
- risk of stopping the fan if I attach the croc-clip wrongly.

# Test  
I tested for continuity between the solder-station fan cage and the earth pin on the solder-station's plug.
*"Beep"*  
It's definitely earthed (wise choice past-Laurence. I always believed in you.)

# Can I quickly make a BETTER connection place to clip the strap to?
## Straight into the wall
- Push a brass earth-pin ([salvaged](shattered%20plug.md) from a broken 3 pin plug) into the earth hole of a 4way mains extension.
- croc-clip ESD strap to the pin

The power switch ***is*** off, but I still don't love this as a point to clip directly to because:
- the brass screw of the earth pin is a bit too small for the croc-clip to make reliable mechanical connection 
- under a table (I might knee it)
- connection is out of sight (might become disconnected and I don't know)
- earth conductor is close to the live hole which is now opened by the inserted earth pin.

If I leave the mains switch off it's safe because the whole socket is not live.
But the set up still feels unnecessarily shonky.

I tested the connection for continuity (one probe on the earth pin, one on the croc-clip) and it looked excellent.

At this time I was diverted, but I learned [how a grounding wrist-strap works](Anti_Static_Wrist_Strap.md).

