# GWaves

This is a challenge proposed in a selection process to participate in a research at my university. 

## The problem
About 100 years ago, gravitational waves were already predicted by the models developed by Albert Einstein. These waves are the result of large-scale events involving the interaction of very massive bodies, such as the collision of black holes, for example. On June 28, 2023, the North American Nanohertz Observatory for Gravitational Waves revealed the detection of low-frequency gravitational waves [1]. The detection of gravitational waves had already been showing its first positive results since 2015.

The detection of gravitational waves through laser interferometers requires extremely high sensitivity to changes in distance. However, because they are located on land, the instruments are subject to non-astrophysical noise, which are known as "glitches," transient instrumental and environmental disturbances that make the search for gravitational waves difficult. The Gravity Spy project is an effort to comprehensively classify glitches, combining the strengths of machine learning algorithms and the work of volunteers who annotate the data. A public dataset was constructed [2], which contains spectrograms representing variations of the spectrum (vertical axis) over time (horizontal axis). Figure 1 illustrates the spectrogram of a glitch:

Figure 1: Spectrogram of a glitch event. Adapted from [3].

1) Write in Python, using Google Colab, the following functions:

a) A function that calculates a vector with the maximum amplitude values at each time, given the spectrogram.

b) A function that calculates a vector with the corresponding frequency values to the maximum amplitude at each time (as described in item (a) above), given the spectrogram.

2) Build a classifier capable of identifying the type of glitch using the vectors obtained with the functions described above.

3) Evaluate your classifier using the metrics you deem appropriate.

[1] https://www.space.com/gravitational-waves-astronomers-why-so-excited

[2] https://www.kaggle.com/datasets/tentotheminus9/gravity-spy-gravitational-waves

[3] S. Bahaadini, V. Noroozi, N. Rohani, S. Coughlin, M. Zevin, J.R. Smith, V. Kalogera, A. Katsaggelos, Machine learning for Gravity Spy: Glitch classification and dataset, Information Sciences, Volume 444, 2018, Pages 172-186, https://doi.org/10.1016/j.ins.2018.02.068.

## Notes

The problem given is related to CNN work. Algorithms like RFC, SVM... can also be used but of course, expecting a lower accuracy. 

