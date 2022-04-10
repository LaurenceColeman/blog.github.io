2022 04 08  

# Is my wrist-strap broken?  
I was exploring my options for anti-static [grounding](grounding_myself.md) myself when I'm building electronics at home.  

For fun, I tried testing between the crocodile clip and the wrist contact of my [Anti-Static Wrist Strap](https://www.ifixit.com/Store/Tools/Anti-Static-Wrist-Strap/IF145-071) for continuity.  
No beep. Apparently there's no connection.

Oh no!  
I assumed I must have walked away from a workpiece while the clip was still attached (I've definitely done this a few times) and accidentally yanked it badly enough to break the conductor.

Have I been using a broken strap?  
Was I putting on a useless, blue wristband each time?  
Worse still, did ifixit send me a strap that didn't work? That would shake my world-view!
    
Cheap ones are only a couple of £s so I bought a new one from eBay.  
The new one also showed no connection between clip and strap. 
Is it likely I had two faulty straps from two different manufacturers?  
It's much more likely I just don't understand how they work.

<a id='tldr'></a>

# It's not just a wire on elastic  
Some quick research showed me that a strap should be about 1MOhm:  
> <a href="https://mulloverthings.com/how-do-you-measure-an-esd-wrist-strap/#What_is_the_specification_of_anti-static_wrist_strap" target="_blank" rel="noopener noreferrer">https://mulloverthings.com/how-do-you-measure-an-esd-wrist-strap/#What_is_the_specification_of_anti-static_wrist_strap</a>  

No wonder the continuity test didn't register any current, it's a long bendy resistor!  
I'd assumed it was just a copper wire with negligible resistance but it makes total sense: you don't want to accidentally short a live current straight through your wrist by accident.

Well, now I have a spare wrist strap!

## resources
___ 

> "(the textile wrist strap is) expected to have an internal resistance of less than 100KOms so that you get a good connection to your skin.  
> ...  
> The external resistance of the band should be more than 10MOhms so you don't accidentally short your board"   
> <a href="https://youtu.be/f3nBl2DrAEA?t=736" target="blank" rel="noopener noreferrer>https://youtu.be/f3nBl2DrAEA?t=736</a>  
> 
___       
