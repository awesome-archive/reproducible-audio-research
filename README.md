## Classes at universities

- Dan Ellis, Brian McFee: [REPRODUCING COMPUTATIONAL RESULTS](http://www.ee.columbia.edu/~dpwe/e6891/)

## Documents about reproducible research

- [Reproducible Research in Signal Processing - What, why, and how](https://infoscience.epfl.ch/record/136640)
- [Reproducible Research with R & RStudio](http://christophergandrud.github.io/RepResR-RStudio/) 

## Online Resources, databases for reproducible work

- http://www.gitxiv.com
- http://rr.epfl.ch
- http://soundsoftware.ac.uk/rr-prize
- http://soundsoftware.ac.uk/handouts-guides

## List of Papers

### Melody Extraction from Polyphonic Music Signals: Approaches, Applications and Challenges
Justin Salamon et. al.

We present a novel system for the automatic extraction of the main melody from polyphonic music recordings. Our approach is based on the creation and characterisation of pitch contours, time continuous sequences of pitch candidates grouped using auditory streaming cues. We define a set of contour characteristics and show that by studying their distributions we can devise rules to distinguish between melodic and non-melodic contours. This leads to the development of new voicing detection, octave error minimisation and melody selection techniques. A comparative evaluation of the proposed approach shows that it outperforms current state-of-the-art melody extraction systems in terms of overall accuracy. Further evaluation of the algorithm is provided in the form of a qualitative error analysis and the study of the effect of key parameters and algorithmic components on system performance. Finally, we conduct a glass ceiling analysis to study the current limitations of the method, and possible directions for future work are proposed.

#### Paper

[Download PDF](http://www.justinsalamon.com/uploads/4/3/9/4/4394963/salamon_gomez_ellis_richard_melodyextractionreview_ieeespm_2013.pdf)

#### Source Code

* [VAMP Binary Code to run in Sonic Visualizer](http://mtg.upf.edu/technologies/melodia)
* [Run vamp plugin from python](https://pypi.python.org/pypi/vamp)
* [C++ Implementation in Melodia](http://essentia.upf.edu/documentation/reference/std_PitchMelodia.html)

#### Datasets used in the Paper

* [ADC2004/MIREX05](http://labrosa.ee.columbia.edu/projects/melody/)

#### Evaluation 

* [mir_eval melody evaluation](https://github.com/craffel/mir_eval/blob/master/evaluators/melody_eval.py)

#### Further Information

* http://www.justinsalamon.com/melody-extraction.html
* http://www.music-ir.org/mirex/wiki/2016:Audio_Melody_Extraction



- Colin Raffel: [Large-Scale Content-Based Matching of Midi and Audio Files](http://www.gitxiv.com/posts/4foCRJSjf8mDrnigq/large-scale-content-based-matching-of-midi-and-audio-files)
- Font, F., & Serra, X. [Tempo Estimation for Music Loops and a Simple Confidence Measure](https://github.com/ffont/ismir2016)
