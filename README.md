# Respiratory-Disease-Classification

The Respiratory Sound Database was created by two research teams in Portugal and Greece. It includes 920 annotated recordings of varying lengths - 10s to 90s. These recordings were taken from 126 patients. There are a total of 5.5 hours of recordings containing 6898 respiratory cycles - 1864 contain crackles, 886 contain wheezes and 506 contain both crackles and wheezes. The data includes both clean respiratory sounds as well as noisy recordings that simulate real-life conditions. The patients span all age groups - children, adults, and the elderly.
The model has been created after converting the audio files into to audio matrix using the MFCCs function after padding all the audio files to 20 seconds to make all the audios of uniform length.
the labeled classes are COPD, Healthy, URTI, Bronchiectasis, Pneumonia, Bronchiolitis, LRTI, and Asthma.  
