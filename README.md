# Yelp-Review
<br />Hello, this is group Foodie. Our project is Review Helpfulness Prediction Based on Multiple Features on Yelp dataset. Link is: https://www.yelp.com/dataset
<br />For our model, we used a cleaned up file (Review_project_sentiment_wUser.csv): https://drive.google.com/file/d/1cVCTHLUClZObvhDZ5EpWarCSLigX-KhO/view?usp=sharing
<br />The Users related information data link is: https://drive.google.com/file/d/1Bh0A4Br-AVrFJ4u5u8tDx5QJdyr6cDj1/view?usp=sharing.The file name is user_selected.csv.

## This file is created by using the following jupyter files: 
<br />Processing initial yelp review json file.ipynb: convert the original review json into csv
<br />Processing initial yelp user json file.ipynb: convert the original user json into csv
<br />Final Data clean.ipynb: text clean and extraction of sentiment features 
<br />Add_user_info.ipynb: Add foreign key features and length of the review

## Model file discription:
<br />TF-IDF ONLY.ipynb: tfidf features only
<br />TF-IDF+ other features.ipynb: tfidf features + sentiment features + foreign key features + review structrual features
<br />fasttext ONLY.ipynb: fasttext embedding
<br />other features only.ipynb: sentiment features + foreign key features + review structrual features
<br />word2vec ONLY.ipynb: w2v only
<br />word2vec+other features.ipynb: w2v features + sentiment features + foreign key features + review structrual features
<br />tfidf+other _blending.ipynb: for tfidf and other features using the method of blending.
<br />word2vec+other_blending.ipynb: for word2vec and other features using the method of blending. 
