The Million Song Dataset (https://labrosa.ee.columbia.edu/millionsong/) is a collection of metadata and precomputed audio features for 1 million songs. Along with this dataset, a dataset with annotations of 15 top-level genres with a single label per song was released. In this work, we combine the CD2c version of this genre datase (http://www.tagtraum.com/msd_genre_datasets.html) with a collection of album cover images. 
The final dataset contains 30,713 tracks from the MSD and their related album cover images, each annotated with a unique genre label among 15 classes. Based on an initial analysis on the images, we identified that this set of tracks is associated to 16,753 albums, yielding an average of 1.8 songs per album.

We randomly divide the dataset into three parts: 70% for training, 15% for validation, and 15% for test, with no artist and album overlap across these sets. This is crucial to avoid possible overfitting, as the classifier may learn to predict the artist instead of the genre. 

Content:

MSD-I dataset (mapping, metadata, annotations and links to images)
Data splits and feature vectors for TISMIR single-label classification experiments 

These data can be used together with the Tartarus deep learning library https://github.com/sergiooramas/tartarus.

Dataset compiled and authored by Sergio Oramas. Copyright ©2018 Music Technology Group, Universitat Pompeu Fabra. Creative Commons Attributions 4.0.


Scientific References:

Please cite the following paper if using MSD-I dataset or Tartarus library.

Oramas, S., Barbieri, F., Nieto, O., and Serra, X (2018). Multimodal Deep Learning for Music Genre Classification, Transactions of the International Society for Music Information Retrieval, V(1).