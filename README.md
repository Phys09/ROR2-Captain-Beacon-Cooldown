# ROR2-Captain-Beacon-Cooldown-and-Tweaks

## Description

A mod for risk of rain 2 that gives cooldowns to captain's beacons,
allowing him to use them more than once on each stage. Has config support.

May be updated later to give more captain tweaks down the line such as the following:

1. Fix diablo strike to actually do "40,000% damage to all characters"
   \- Ability Description

   - Currently, the ability does 40,000% damage to targets in the inner half
     radius, and 10,000% outside that half radius (sweetspot falloff).

2. Allowing usage of captain orbitals in areas where they are usually disabled.
   - Such as the bazaar, or the void fields.

## Bandoliers don't work

Bandoliers do not work with beacons partially for balance, but mainly
due to the beacons having weird
stopwatch behaviour that I wasn't able to enable/fix.
May be fixed in the future.

## Default Beacon Cooldowns

- Healing Beacon: 40s
- Shocking Beacon: 40s
- Equipment Beacon: 60s
- Hacking Beacon: 180s

Note to source code readers:

The source code will look like it's been hacked together because it has been.

This is because trying to just change the cooldowns, max stack size,
stack size, etc... of the beacons loaded in seemed to give weird behaviour, likely
due to how the beacons were not meant to be given cooldowns
so there is no stopwatch ticking for them.

The mod otherwise works given the current implementation,
but it's still possible that the implementation could have been better.
