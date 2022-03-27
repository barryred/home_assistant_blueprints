# Sengled Smart Light Switch, Perscriptive Blueprint for zigbee2mqtt
This ties a Sengled smart switch to one 'light' in a *very* simple (but also perscriptive) way.

**Notes:**

This only controls the brighness of the light (i.e. color and color-temp are left unchanged)

The only thing that MUST be configured, are the 'Light Switch', and target 'Lights', however, much else is configurable.

### The Buttons are mapped as follows:
&copy; below implies that the value is configurable.
* on: Immediately to 50% &copy;
* double-on: Immediately to 100%
* off: Immediately off.
* double-off: Immediately off. (looking for suggestions for better use of this.)
* up: Immediately +10% &copy;
* down: Immediately -10% &copy;
* long-on: Fade on to the same 'on' value (default 50%), over 7 seconds &copy;
* long-off: Fade off over 7 seconds &copy;
* long-up: Fade up by 30% &copy; over 1 second &copy;
* long-down: Fade down by 30% &copy; over 1 second &copy;

Related Links:
https://www.zigbee2mqtt.io/devices/E1E-G7F.html
