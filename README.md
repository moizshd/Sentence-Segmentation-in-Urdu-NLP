# Sentence Segmentation in Urdu NLP
 Getting my hands on experience of how Urdu sentence segmentation will work. Better algorithms are available.

My goal is to implement and practice some basic concepts of NLP in the 
Urdu language. The Urdu language is written in different styles as compared to the English 
language. Urdu Word Segmentation is a challenging task. There can be several reasons but 
Space Insertion Problem and Space Omission Problems are the major ones. So, in this 
assignment, our task is to do Urdu sentence segmentation. This assignment is designed to be 
completed from scratch. You are free to use basic libraries if you are comfortable doing so and 
you can improve existing libraries like urduhack. 

2 Background 

Sentence segmentation is the process of determining the longer processing units consisting of 
one or more words. This task involves identifying sentence boundaries between words in 
different sentences. For this assignment, you are given an Urdu corpus. Here is an example of 
text combination of two sentences: 
تبدیلی سرکار’’ کی چکنی چپڑی باتوں ٔے ‘‘ بے چاری عوام چونکہ ہمیشہ سے دھوکہ کھانے کی عادی رہی ہے اس لی
ٓگٔیی اور اپنے بہتر مستقبل کے لٔیے نٔیی حکومت کو اقتدار کے ایوانوں تک پہنچا دیا
میں ا
I trained a model that will perform segmentation of sentences and remove extra white 
spaces in sentences for example by passing the above statement, your model should generate 
output: 
تبدیلی سرکار“ کی چکنی چپڑی باتوں ٔے ” بے چاری عوام چونکہ ہمیشہ سے دھوکہ کھانے کی عادی رہی ہے۔ اس لی
ٓگٔیی اور اپنے بہتر مستقبل کے لٔیے نٔیی حکومت کو اقتدار کے ایوانوں تک پہنچا دیا۔
میں ا


3 Challenges in Implementing a Model 

• How will you extract patterns from the text?
• How will you identify Urdu End words of a sentence?


