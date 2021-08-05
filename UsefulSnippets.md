# Useful YOLOL Snippets for Starbase

## Generator

This is my favourite setting. It's aggressive enough so you're not often short of battery unless you're dry-humping them with lasers.
```
:GeneratorUnitRateLimit = 1000.1- :StoredBatteryPower/10 goto 1
// use 1000.1 to avoid stuttering
```


## Controls

Cute little script to use a centering lever for throttle. Holds position if forward, auto centres backward.

```
:fcuBackward=-:fcuForward if :fcuBackward>0 then :cruise=100 end goto1
// where cruise is leverCenteringSpeed 
```

