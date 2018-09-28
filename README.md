# resistance-vs-temperature

RvsTemp_Lakeshore_crh.vi

This LabView software was developed for recording resistivity vs temperature using a Keithley sourcemeter and LakeShore temperature controller.

Note that communication with either device can be toggled on and off. (Useful for debugging communication issues.)

Hardware Requirements
---------------------

Temperature Control: LakeShore 331
SourceMeter: Keithley 26XX series (tested with 2635A)

Labview vi Requirements
-----------------------

Saving data:
> Save-Pulse-RvsT.vi
  Source: Included in this repository

Communicating with LakeShore 331 temperature controller:
> lsci331u.llb
> lsci331.llb
> LS331-temp-cntrlvi.vi
> Lake Shore Cryotronics 331.lvlib (for Labview 8.5)
  Source: http://sine.ni.com/apps/utf8/niid_web_display.download_page?p_id_guid=7094CC81B2146DD9E04400144FB7D21D

Communicating with Keithley 26XX sourcemeter:
> KE26XX.lvlib
> KE26XX-SM-close.vi
  Source: https://www.tek.com/source-measure-units/2635-software/keithley-series-2600-2600a-2600b-native-labview-2009-instrument-d
