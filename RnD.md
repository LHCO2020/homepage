## LHC Olympics 2020 R&D Page

For setting up, developing, and validating your methods, we provide background events and a benchmark signal model.  You can download these from [this](https://zenodo.org/record/2629073#.XKdewGXlRg0) page.  To help get you started, we have also prepared [simple python scripts](https://github.com/lhcolympics2020/parsingscripts) to read in the data and do some basic processing. 

<!--- The final test will happen 2 weeks before the ML4Jets2020 workshop.  We will release a new dataset where the "background" will be similar to but not identical to the one in the development set (as is true in real data!).  The goal of the challenge is to see who can "best" identify BSM (yes/no, what mass, what cross-section) in the dataset.  There are many ways to quantify "best" and we will use all of the submissions to explore the pros/cons of the various approaches. ---> 

To keep the scope limited, all signals will be of the form X -> hadrons, where X is a new massive particle with an O(TeV) mass.  The events require at least one R = 1.0 jet with pT > 1.2 TeV.  For each event, we provide a list of all hadrons (pT, eta, phi, pT, eta, phi, ...) zero-padded up to 700 hadrons.

We strongly encourage you to publish your original research methods using these datasets (before or after) the unveiling of the results.  Anyone who participates will be part of a summary paper to be prepared following the workshop.

Please do not hesitate to ask questions:  we will use the [ML4Jets slack channel](https://join.slack.com/t/ml4jets/shared_invite/enQtNDc4MjAzODE0NDIyLTU0MGIxNmZlY2E4MzY2YzEwNGI2MGI5MzJmMzEwODVjYWY4MDFhMzcyODYyMDViZTY4MTg2MWM2N2Y1YjBhOWM) to discuss technical questions related to this challenge. 

Good luck!

_Gregor Kasieczka, Ben Nachman, and David Shih_

