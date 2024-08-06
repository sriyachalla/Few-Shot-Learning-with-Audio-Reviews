# Few-Shot-Learning-with-Audio-Reviews

### Abstract :
In this project we perform Few Shot Learning with audio reviews that are obtained from our app - Hot Takes. The goal is to be able to understand our customer base better and make informed data driven decisions that will align with the needs and wants of our customers. In particular, we will be marking the content of the reviews as offensive or not, rate the positiveness of a review and provide a short 3 to 5 word summary of the audio take. To that end, we leverage OpenAI’s Whisper API to transcribe the audio reviews to text, then their ChatGPT API to categorize them, all in an automated manner.

### Background:
Our objective is to better understand our customers and their sentiments by transcribing and analyzing audio reviews for our startup - Hot Takes. Analyzing the audio reviews will help us make informed data-driven decisions that align with our customers needs and wants, including recommendations of places through fun reviews that are positive and persuasive.
Our project builds off of related work on Few-shot Learning in the Natural Language Processing space. In the context of audio reviews, transcribing involves using speech recognition technology and we will later use NLP and Few Shot Learning to conduct sentiment analysis on textualized review data to recommend places that are fun through positive and persuasive reviews.
Our challenge is to see how few examples can get to a high enough accuracy. Fast Forward labs released a paper that is closest to what we are doing, and in it they train Sentence-BERT for few-shot classification and analyze the accuracy by comparing it with some out of the box large language models.

### Dataset:
We are using the data from the Beta version of our app. As of now we have 200 Takes that we are transcribing using OpenAI’s Whisper API.This data is stored in firebase as audio files. The dataset includes information about reviews of places that people have visited like cafes,
 restaurants, shopping malls etc. There may be some bias in the dataset based on the customer’s willingness to record the review and the review might not be a representative sample of the customer base. However the data set will give valuable insights into the sentiment analysis of customers and will be of great use for future business decision making.
