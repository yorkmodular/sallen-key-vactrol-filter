### Sallen-Key Vactrol LPF

**This module is now discontinued - there will be no more made unless there is sufficient demand to justify a new run of boards and panels.**

**Information provided here is provided under the terms of the Creative Commons License Attribution-ShareAlike 4.0 International**

A VCF finally hits the line-up

Filters don't need to be massively complex to sound good, and it's amazing the sort of noises you can get out of an op-amp and a bunch of passive components.

There's an input and output, of course, plus a CV input with an attached attenuator which feeds into a pair of vactrols, which is where the magic happens. 
With a bit of care, you can get everything from nice filter sweeps all the way up to squonky acid-bass and beyond.

The board is laid out based on the assumption that VTL5C3 vactrols (or similar) will be used. Whilst there's no technical reason why DIY vactrols can't be used, 
it may be necessary to mess around with component values - should you go down this route, I recommend socketing the vactrol limiting resistors (R4, R5) and the 
filter capacitor (C3) and fiddling with values until you find a combination that you like.

If you bought the full kit, you'll have received 'sensible' values for the limiting resistors (470k) and filter cap (330pF) - these values aren't set in stone; feel free to experiment. The two resistors can be considered optional (ie. don't fit them if you don't want to) but the capacitor is essential - 330pF is the value I normally use for pre-builts; you can go larger if you wish but keep in mind that if you overdo it you'll end up with a very muffled sound. Along similar lines, reducing the value of C3 will make the filter sound 'sharper' - going lower than around 47pF is not recommended, because it'll sound terrible.

If you wish to get your own boards fabbed, you'll find what you need in the `gerbers` directory.