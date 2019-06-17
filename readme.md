# vocalMashup
Creates a mashup from a given vocal recording and a list of background instrumental tracks. 

### How it works 
Computes tempo, beat and key from vocal and background tracks to find the best match.   
All the algorithms are from [librosa](https://librosa.github.io/librosa/).  

### How to use 
I added some test audios from online and [musdb18](https://sigsep.github.io/datasets/musdb.html).   
1. Put background tracks you want to mash into `background_tracks` directory. 
2. Run the following
```
python mashability.py test_vocal.wav
```

### To do
* Better algorithms for feature computations 
* Better mixing technique


### Projects using this code
* "Learning a Joint Embedding Space of Monophonic and Mixed Music Signals for Singing Voice" - Kyungyun Lee, Juhan Nam, ISMIR 2019
