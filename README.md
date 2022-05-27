# Spam-Detection-using-Machine-Learning

## The Problem
With the rapid development of internet, there are several loopholes that are created in cyberspace and is under constant threat from being exploited by hackers. Growing internet and the increasing importance of emails in our daily lives, spams have become a common phenomenon posing serious threats, as it gives rise to undesired emails. One of the most common threats is that of spam. Hackers and spammers are using innovative and novel techniques to deceive both novice and experienced internet users. Spam consumes vital computation power and resources. Thereby, it becomes important to filter out the spam contents. Nowadays, spam is transmitted via different medium such as images, sms etc. Both the text and image spam messages are developed in such a manner that it surpasses through the traditional spam filters and firewall technologies. Mitigating image spam is even more challenging as they scramble or embed the content in the images in a way which make the detection process extremely difficult.

## Our Solution
In our work, we would be developing frameworks for classifying both texts as well as image contents for spam and ham. We have followed a novel implementation strategy for text spam and image spam classifier model where we attempted to cover the loopholes in the existing techniques and present our approach. From our previous implemented approaches, we have observed that SVM performs the best for spam classification in text. Additionally, a major problem which plagues the domain is class imbalance with significantly higher number of ham messages than spam. Most of the works involved in this domain didn’t solve this issue. So, we have attempted to solve the problem by upsampling the spam messages as it is a minority class. Additionally, we have made use of lemmatization rather than stemming as it provides better results by performing an analysis that depends on the word's part-of-speech and producing real, dictionary words. In the case of image spam, we have observed that most of the works focus on either content-based features (i.e., extracting the text and predicting it whether it is spam or not) and non-content-based features (i.e., color, contrast, brightness etc.). We have ensembled both content and non-content-based features to improve the model robustness. For content-based spam classification, we have used SVM whereas non-content-based spam classification, we have used CNN. Finally, we have used spam score as the metric for adjudging a give message or an image as spam or ham which presents an overall picture of it being ham or spam.

### Input for Text Spam
<img width="451" alt="image" src="https://user-images.githubusercontent.com/53989824/170784249-f5e23936-4d9d-492c-b6c5-313568246bea.png">

### Input for Image Spam

<img width="451" alt="image" src="https://user-images.githubusercontent.com/53989824/170784273-42bd6007-53c0-46ac-bd0c-dae3ec0b090d.png">


### Text Spam Detection

<img width="405" alt="image" src="https://user-images.githubusercontent.com/53989824/170784296-93149778-f865-48fe-be1c-d61d66a48ec4.png">

### Text Ham Detection

<img width="404" alt="image" src="https://user-images.githubusercontent.com/53989824/170784327-2387d43f-298f-4b21-8aed-ef4530030637.png">

### Image Spam Detection

<img width="358" alt="image" src="https://user-images.githubusercontent.com/53989824/170784375-5ec25d16-be2d-41ae-bbcc-301e31c43566.png">

### Image Ham Detection

<img width="266" alt="image" src="https://user-images.githubusercontent.com/53989824/170784426-0d8eedb8-c402-43f0-a001-b593dbc2e679.png">


