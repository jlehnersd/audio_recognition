# Audio Recognition

---

## Proposal

### Data set

For my project, I will use Google's AudioSet data set, which contains over two million 10-second clips of sounds from YouTube videos. All clips have been classified by humans into over 600 classes of sounds. For example, classes include glass breaking, dogs barking, person laughing, engine starting, etc.

### End goal

I want to build a classifier that idenitfies AudioSet sounds. To limit the scope of the project, I will choose one or two dozen classes of sounds only. For fun, I will limit the classes to sounds that are commonly heard in horror films. My ultimate goal is to have my classifier identify sounds in videos and automatically close caption them with the correct sound description. As proof of principle, I want to make a 30-second film noir that includes sounds from some of the classes I used to train my model. The film will include the automatic closed captions that are determined by my model.

### MVP

My MVP is to have a pipeline that correclty extracts my audio data from the YouTube video clips and processes that data so that it is in a form that is suitable for analysis by a machine learning model. My MVP+ is to use that data to train a model that is able to classify individual sounds with good accuracy (in colloquial terms).

### Plan B

I have no plan B yet. YOLO!