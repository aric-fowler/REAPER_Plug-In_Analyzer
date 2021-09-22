# REAPER_Plug-In_Analyzer
Files for measuring the frequency and dynamic response of audio effects plug-ins using the REAPER digital audio workstation (DAW)

Developed in REAPER v6.34

The analyzer is available in track template and project template formats. Both template use only stock (Rea or JS) REAPER plug-ins 
for analyzing a "plug-in under testing". Please note that the project version does not observe a pan law, but the track template 
will observe the pan law of the project it is used in. This can result in inaccurate readings if pan law is used!

The current version (v1.0) currently supports L/R stero and mono plug-ins. M/S processing can be analyzed but requires routing
modification and the inclusion of the Mid/Side Encoder and Mid/Side Decoder JS plug-ins. The analyzer works best with filter/EQ,
compressor, and distortion-type effects plug-ins. 

Any questions/comments/concerns regarding the analyzer can be directed at: aricdfowler@gmail.com
