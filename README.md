# Facial Emotion Recognition
Facial emotion is the main factor for multiple culture
communication by visual.[6]. Facial emotion detec-
tion is the most vital plays in medical and Research
purposes. In the facial emotion recognition most im-
portant of the model is finding the eyes at correct
location [27].
With the need of human–computer interaction,
the emotion recognition plays an important role in
computer science. There are a lot of ways to recog-
nize emotion included through voice, body gesture,
specially facial expression what is the most impor-
tant way for human to display emotions. In fact,
facial emotion recognition has been applied for a lot
of applications of variety fields such as customer –
attentive marketing, health monitoring and emotion-
ally intelligent robotic interface. Therefore, research-
ing about facial emotion recognition has increasingly
attracted many scientists in computer vision.
In 1971 paper titled “Constants Across Culture in
the Face and Emotion”, Ekman et al. identified six fa-
cial expressions that are universal across all cultures:
anger, disgust, fear, happiness, sadness and surprise.
In recent years, research challenge such as Emotion
Recognition in the Wild (Emotion) and Kaggle’s Fa-
cial Expression Recognition Challenge added the sev-
enth emotion, neutral emotion, into this list for clas-
sification.
The first successful applications of CNNs were de-
veloped by Yann LeCun in 1990’s. Of these, the best
known is the LeNet architecture that was used to read
zip codes, digits, etc.[20]Day by day, CNNs has been
developing by the scientist community. Specially, in
computer vision, there are a lot of momentous works
which use CNNs approach such as AlexNet[4], VGG-
Net[16], GoogleNet[5], and ResNet[15]. Besides, there
are some contribution from public challenges, typi-
cally Facial Emotion Recognition challenge in Kaggle
(2013) and Emotion Recognition in the Wild chal-
lenge (2015).
In this paper, we executed CNNs approach for
facial emotion recognition. The input in to out
system is image from Kaggle dataset, then we use
CNNs to train and predict the label facial expres-
sion, consist of angry, disgust, fear, happy, sad, sur-
prise, and neutral. We tried to build distinct CNNs
systems with various layers to find out the best per-
formance. We reached 65.55% of highest accuracy.
It can be accepted because the winner of FER2013
challenge achieve 71.162% accuracy. Not only accu-
racy achieved, we also found some interesting things
about CNNs. Although our result and method is not
the best, it made us understand deep learning obvi-
ously and easier to implement it.This experiment gave
us a basic knowledge for out future work. There is a
possibility of detecting the emotion wrong like when
the person is fake smiling, we might get the results
wrong, and the data is not labelled correctly we might
have a problem in detecting the facial expression over
the time.
Through this experiment, we learn how to imple-
ment a CNNs model to solve a real life problem. In
future, we would like to implement a deeper CNN
with a paramaterizable number of convolutional lay-
ers, and check that if more number of convolutional
layers, the higher accuracy is. Moreover, we would
like to extend our model for color images with in-
vestigating pre-trained models such as VGG-Net [16]
and AlexNet[4].


