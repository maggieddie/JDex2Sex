JDex2Sex
========

A code generator(transformer) to generate Dalvik Smali (Jasmin) in S-Expression format.

It is built on top of dedexer project by Paller: http://dedexer.sourceforge.net

This project is also meant to serve as the front end to work with Dalvik analyzer.


Additional notes:

apks -- place where you put your testing .apk files to generate IRs.
       	       if you don't want to use the IRs provided in analyzer.
	       Instructions on how to generate IRs in analyzer: pdafordalvik

get-ir.py -- a script using apktool and jdex2sex to generate IRs
       		    into apks folder

Please go into folder "pdafordalvik" and refer README.md on how to run analyzer directly.


