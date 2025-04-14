# ascript-pgmConverter
.ascript与.pgm转换

V0.1  
|pgm|convert|ascript|convert
|---|---|---|---|
|'|//|//|'|
|G|G|||
|LINEAR|G1|G1|LINEAR|
|RAPID|G0|G0|RAPID|
|CW|G2|G2|CW|
|CCW|G3|G3|CCW|
|DWELL|G4|Dwell()|DWELL|
|ENGLISH|G70|G70|ENGLISH|
|METRIC|G71|G71|METRIC|
|MINUTES|G75|SetupTaskTimeUnits(TimeUnits.Minutes)|MINUTES
|SECONDS|G76|SetupTaskTimeUnits(TimeUnits.Seconds)|SECONDS|
|ABSOLUTE|G90|SetupTaskTargetMode(TargetMode.Absolute)|ABSOLUTE|
|INCREMENTAL|G91|SetupTaskTargetMode(TargetMode.Incremental)|INCREMENTAL|
|VELOCITY ON|G108|VelocityBlendingOn()|VELOCITY ON|
|VELOCITY OFF|G109|G109|VELOCITY OFF|
|ENABLE|Enable([])|Enable([])|ENABLE|
|PSOCONTROL X ON|PsoOutputOn()|PsoOutputOn()|PSOCONTROL X ON|
|PSOCONTROL X OFF|PsoOutputOff()|PsoOutputOff()|PSOCONTROL X OFF|
|PSOCONTROL X RESET|PsoReset()|PsoReset()|PSOCONTROL X RESET|
|WAIT MOVEDONE X Y Z|WaitForMotionDone([])|WaitForMotionDone([])|WAIT MOVEDONE X|
|PROGRAM||||
|PSOOUTPUT||||
|G359|G359|G359|G359|
|G92|G92|G92|G92|
|||program||
|||end||
