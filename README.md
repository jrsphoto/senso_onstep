# senso_onstep
PrimaLuce Sesto Senso focuser conversion to Onstep

My old PrimaLuceLab Sesto Senso focuser wasn't cooperating anymore. The control board wasn't booting, and contacting PrimaLuceLab didn't help as the device was out of production. Throwing away the entire metal body just felt wrong, especially considering the 1.8-degree Nema 14 stepper motor inside.

Since I already use Onstep for my telescope's motion control (which also supports focus motors), I decided to reuse the focuser. I created a replacement electronics board with a stepper motor connection and an RJ22 jack that fits perfectly in the original DC power jack's spot. I even designed a new, 3D printed top cover with mounting points for the new board.

The conversion process is super straightforward:

Unscrew the white top cover.
Remove the old electronics, leaving only the stepper motor.
Mount the new PCB in the cover using the dedicated points.
Connect the stepper motor to the PCB.
Screw the cover/PCB assembly back onto the focuser body.
You're done!

This upgrade breathes new life into my old focuser, utilizing its existing motor and integrating seamlessly with my existing setup. No more wasted components, just a revitalized focuser!
