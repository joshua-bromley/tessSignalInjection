# tessSignalInjection

A group of functions to add signals to TESS light curves

The functions can be divided into 3 parts:

Importing Light Curves: Light curves are imported in the form of pickle files, normalized and any time gaps are filled

Generating Light Curves: A light curve is generated using EightBitTransit. It is then extended to match the size of the imported light curve. If it is desired that the generated light curve is periodic, the periodic behavior can be extended

Summing Light Curves: Sums the imported and generated light curve assuming noise is independent of flux. Re adds time gaps to match original curve

The lightcurves folder contains the files for imported light curves, the output folder contains images of the graphs of outputted light curves

EightBitTransit can be found here: https://github.com/esandford/EightBitTransit

Disclaimer: If any of the code is written in an obtuse way for python, is in a wierd order or the files are wierdly organized, it's becuase I'm a C++ programmer writing in python syntax. You'll just have to bear with me
