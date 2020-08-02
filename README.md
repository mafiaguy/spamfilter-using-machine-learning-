# spamfilter-using-machine-learning-

ALL the code and dataset in this repositry are from the BOOK Machine Learning for Cybersecurity Cookbook by Emmanuel Tsukerman. This is me learning from this book and
implementing it and posting it on my github repo. The link to the book is:- https://www.amazon.in/Machine-Learning-Cybersecurity-Cookbook-algorithms-ebook/dp/B081SS5RG2

Here, is a code  for spam-ham (non-spam) classification using machine learning

# Getting ready
Preparation for this recipe involves installing the scikit-learn package in pip. The command is as
follows:
pip install sklearn
In addition, extract spamassassin-public-corpus.7z into a folder named spamassassin-public-corpus.

# How it works
Start by preparing a dataset consisting of raw emails (Step 1), which the reader can
examine by looking at the dataset. In Step 2, we specify the paths of the spam and ham emails, as well as assign labels to their directories. We proceed to read all of the emails into an array, and create a labels array in Step 3. Next, we train-test split our dataset (Step 4), and then fit an NLP pipeline on it in Step 5. Finally, in Step 6, we test our pipeline. We see that accuracy is pretty high. Since the dataset is relatively balanced, there is no need to usespecial metrics to evaluate success.
