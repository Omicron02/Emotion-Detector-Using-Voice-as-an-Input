# Emotion Detector Using Voice as in Input

The aim of the project is to analyze the user's voice and determine their mood which can then be used for various purposes.

Companies can provide a more personalised experience by recommending products based on the person's mood. One such example being in voice assistants. When the user asks it to play a song for example, it can play a song based on the user's mood.


### Datasets:

[RAVDESS](https://zenodo.org/record/1188976):
This dataset includes around 1400 audio file input from 24 different actors. 12 male and 12 female where these actors record short audios in 8 different emotions i.e 1 = neutral, 2 = calm, 3 = happy, 4 = sad, 5 = angry, 6 = fearful, 7 = disgust, 8 = surprised.
Each audio file is named in such a way that the 7th character is consistent with the different emotions that they represent.

## Audio files:
Tested out the audio files by plotting out the waveform and a spectrogram to see the sample audio files.<br>
**Waveform**<br>
![](images/wave.png)
<br>
<br>
**Spectrogram**<br>
![](images/spec.png)
<br>

## Predictions

These are a sample of the actual vs predicted values.
<br>
<br>
![](images/predict.png)
<br>

## Testing out with live voices
In order to test out our model on voices that were completely different than what we have in our training and test data, we recorded our own voices with dfferent emotions and predicted the outcomes.<br>
Waveform of recorded audio.
![](images/userinput.png)
<br>
<br>
Output of user's voice data.<br>
![](images/useroutput.png)

# Contributors
* ### [Niranjan Rao S S](https://github.com/NiranjanRao07)
* ### [Noel Jacob Abraham](https://github.com/NoelJacobAbraham)
* ### [Prajay V K](https://github.com/PrajayVK)
* ### [Rahul Samal](https://github.com/Omicron02)
* ### [Ram Selvaraj](https://github.com/ramselvaraj)
* ### [Shafiudeen Kameel](https://github.com/ShafiudeenKameel)
