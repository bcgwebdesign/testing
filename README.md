# Repo for my own things so I don't lose them!

Just my testing repo for now

## garage_safe DEPRECATED in favour of home assistant and all its magic
After our garage door(s) being left open accidentally I re-purposed my Raspberry Pi Zero W to do a bit of work.

Got a bunch of magnetic door position switches and wired it up without any issues.

It roughly follow this logic.

1. Check state of each switch
2. If it has changed (ie open to closed, closed to open, or on power on) then send slack message to my 'monitoring' channel
3. If it has been at open for X minutes then send a reminder every X minutes

Maybe plan to incorporate it into own RPi house alarm at some stage.
