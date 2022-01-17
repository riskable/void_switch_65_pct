# Void Switch Reference PCB Implementation

A reference implementation of an analog hall effect keyboard (65%) that uses 3D printed Void Switches and a Black Pill (STM32F4x1CEU6) microcontroller board.

__WARNING:__ I haven't had a chance to order and test this yet!  Use at your own risk!  YOU HAVE BEEN WARNED!

![OpenSCAD Customizer](/assets/images/void_switch_65_pct_front.png)

Inside this repository is a Kicad 6 project that has everything you need to get started making an analog keyboard PCB that uses 3D printed [Void Switches](https://github.com/riskable/void_switch).  It was made as part of a tutorial that is currently being worked on.  In the mean time--if you know what you're doing--feel to use it as a reference for creating your own analog keyboard PCBs.

![OpenSCAD Customizer](/assets/images/void_switch_65_pct_back.png)

# Included footprints and symbols

The [void_switch_kicad](https://github.com/riskable/void_switch_kicad) repository was added as a `git submodule` so don't forget to run `git submodule foreach git pull` from time to time in order to make sure it stays up-to-date.

There's also:

 * `kicad_misc_parts` which for now just includes a single footprint for a vertical QWIIC/4-pin JST connector that happens to be easy to obtain right now (damn you, parts shortage!).
 * `kicad_blackpill` which contains a simple symbol and footprint for the WeAct Studio Black Pill board.  If you're wondering about the staggered pins it's just a neat way to make hand-soldering a bit easier (it holds the headers in place while you solder; so they won't shift around/lean/fall out).

# Tutorial and OpenSCAD case/plate files are coming soon!

Remember folks: This is my hobby, not my full time job =)
