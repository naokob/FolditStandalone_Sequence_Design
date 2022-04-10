# FolditStandalone_Sequence_Design
This is an xml file to run RosettaScript on Foldit Standalone and do FastDesign based on a resfile.


## Requirements
Foldit Standalone must already be installed.
Foldit Standalone can be downloaded under license from the following link
https://els2.comotion.uw.edu/product/foldit-standalone


## About resfile
Resfile syntax and conventions
https://www.rosettacommons.org/docs/latest/rosetta_basics/file_types/resfiles

The resfile used in the demo was generated using gcndesign_resfile.py from Dr. Shintaro Minami's GCNdesign and modified.

GCNdesign
https://github.com/ShintaroMinami/GCNdesign


## Usage
* Rewrite the filename of ReadResfile in this xml file with the absolute path where your resfile is located.
* Launch Foldit Standalone and import the design template structure　--->　Click on the green "foldit" icon　--->　Click on the orange "Main" icon　--->　Select "Run RosettaScript" in "Menu"　--->　Select and open the xml file.
* It takes from one to several hours to design one structure.
