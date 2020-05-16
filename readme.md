# monoprice_6zone_31028
Custom Home Assistant component for the Monoprice 6-zone Amplifer (Product ID 31028)

### Use at your own risk

This is a rough clone of the monoprice component in Home Assistant core. This is the bare minimum. I would like to finish it and get it added to core, but it's not there yet. No testing has been configured, and the config flow is missing labels on fields, there are a few other labeling type issues which I couldn't hurriedly reverse-engineer. But, it appears to be working after light testing. Fixing the remaining issues is probably stupidly easy, but it isn't at the top of my current list of chores.

To use, drop this directory into your config/custom_components directory, so it should look like: `config/custom_components/monoprice_6zone_31028`

You may have to restart home assistant. Make sure your amp is connected.

Add the amp via integrations. You will be presented with a blank config dialog with three blank lines.

The top one should be the the location of your amp, ie: `/dev/ttyUSB0`. 

The second two are the source names for the LINE and BUS, LINE being the "primary" input and BUS being the direct zone input.