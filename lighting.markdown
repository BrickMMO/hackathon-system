## Lighting

![Lighting](images/lighting.png)

> <small>LEGO (n.d.). LEGO Motorized Lighthouse. Retrieved Feb 10th, 2024, from [https://www.lego.com/en-ca/product/motorised-lighthouse-21335](https://www.lego.com/en-ca/product/motorised-lighthouse-21335)</small>

### Description

This system will provide lighting...

### Requirements

This interaction will only require a EV3 hubs, lights, and extensions:

<img src="/media/ev3/brick.jpg" height="200">
<img src="/media/power-functions/lights.jpeg" height="200">

## Pseudocode

This example will turn lights on when a grid is "on" and turn the lights off when a grid is "off":

```pseudocode
REPEAT-EVERY 30 Seconds

    FOREACH Grid

        IF GridStatus== "On" THEN

            TurnGridLightsOn

        ELSE

            TurnGridLightsOn

        ENDIF

    ENDFOREACH

ENDREPEAT
```

[&#10132; Back to Hackathon](/hackathon-system)

---

<a href="https://brickmmo.com">
<img src="https://brickmmo.com/images/brickmmo-logo-horizontal.jpg" width="100">
</a>
