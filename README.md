# Hand-to-Doc---NLP
this is a NLP projects which converts handwritten text doc to system doc.

Algorithms used : 
-> Horizontal histogram projection for line segmentation,
-> Vertical Projection Profile (VPP) for word segmentation 
-> Average of VPP and TDP(Top Down Profile) for character segmentation
-> CNN was used for Character Recognition 

Work Flow :
-> Cleaning the data sets
-> take the text doc as input
-> Pre-Processing (removing all disturbance and various marks on text doc to avoid incorrect results)
-> line segmentation to divide all the lines in text doc
-> word segmentation to divide every single word in each line
-> after word segmentation we perform combine word to combine the characters which were considered as words and seperated in above step
-> character segmentation to seperate characters in every single word and store it.
-> on using CNN we recognise each single character which were stored in above step.


#data sets#
the data sets size is huge. 
so the link for data set is : https://www.kaggle.com/srinukesari/characters

#code is developed using Kaggle platform 
