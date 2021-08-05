

# HoudiniPythonResampler

All written in Python.

Includes the following functions:

**SingleResample** (emulates standard Houdini resample functionality) <br>
**MultiResample** (for resampling with different gap lengths) <br>
**RampResample** (for parametric resampling using a ramp Parameter) <br>
**RandomResample** (not yet implemented)

Every resample function uses the master function TrueResample.

The .hdalc file contains also the following nodes: <br>
**Resample_CarveHelper** - for helping with separating Ramp Resamples and breaking them up into different curves <br>
**Resample_IdentityCurve** <br>
**Resample_HalfCircle** <br>







***Ramp (Parametic) Resample w/ Carve Helper:***

![ExampleImage](https://github.com/erictktk/HoudiniPythonResampler/blob/master/rampresampleexample.png)
