# Python implementation of Krippendorff's alpha – inter-rater reliability

For <a href="http://en.wikipedia.org/wiki/Inter-rater_reliability">inter-rater agreements</a> for experimental data with missing values, <a href="http://en.wikipedia.org/wiki/Krippendorff's_Alpha"><em>Krippendorff's alpha</em></a> coefficient has been established as a standard measure.
This a very general implementation in the <a href="http://python.org">Python</a> programming language, allowing the use of arbitrary metrics. It is also accelerated for some standard metrics that allow vector math (through <a href="http://numpy.scipy.org">Numerical Python</a>) -- currently nominal, interval and rational metrics.
