# lip-reading-deeplearning

### What is Lip Reading ?
Lipreading plays a crucial role in human communication and speech understanding. It is a notoriously difficult task for humans, specially in the absence of context1 . Most lipreading actuations, besides the lips and sometimes tongue and teeth, are latent and difficult to disambiguate without context. Machine lipreading is difficult because it requires extracting spatiotemporal features from the video (since both position and motion are important). Recent deep learning approaches attempt to extract those features end-to-end.
In this project, we present LipNet, which is to the best of our knowledge, the first end-to-end sentence-level lipreading model.
This Project has been built upon the paper “LIPNET: END-TO-END SENTENCE-LEVEL LIPREADING” ![image](https://github.com/VedantMankar/lip-reading-deeplearning/assets/51293708/8042a4b7-1997-491d-aedf-5fbf3eb64e2b)


### Dataset
The Data has been taken from ‘GRID Corpus’. GRID is a large multitalker audiovisual sentence corpus to support joint computational-behavioral studies in speech perception. In brief, the corpus consists of high-quality audio and video (facial) recordings of 1000 sentences spoken by each of 34 talkers (18 male, 16 female). Sentences are of the form "put red at G9 now".  The corpus, together with transcriptions, is freely available for research use. The Dataset link is here.
![image](https://github.com/VedantMankar/lip-reading-deeplearning/assets/51293708/f942e261-6d2c-44c1-9832-26a83ba3cec5)


### Deep Neural Network
![image](https://github.com/VedantMankar/lip-reading-deeplearning/assets/51293708/7527d114-c908-4a36-b7ca-8bf7e539476e)


After training and saving the above model. We built a web app to display how the model predicts

### Web Application using streamplit
![image](https://github.com/VedantMankar/lip-reading-deeplearning/assets/51293708/3b7f7588-7361-4d09-ba16-a98213f9784d)


### Future Works and Application
In Future I plan to make a web based application which lipreads real time video
Propose a different model architecture which would be better than this one 
Open to diverse dataset (i.e video samples)
The LipNet model can be applied to videos with low audio quality to better understand the speaker.

