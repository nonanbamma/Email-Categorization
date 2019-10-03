# Email-Categorization
Automatic email classification and categorization into organized bundles.

The purpose of this project is to classify email smartly based on the body of the mail using NLP and ML leveraging Python's scikit-learn library. The data used for this experiment is made publicly available by Enron Corp.

The data is to be downloaded from the link: http://bailando.sims.berkeley.edu/enron/enron_with_categories.tar.gz and extracted into the data/folder. The data directory should look like this after data extraction into it. data/enron_with_categories/1/2/3/4/5/6/7/8/ 

The data folder categories.txt(http://bailando.sims.berkeley.edu/enron/enron_categories.txt):The categories which are used to label the emails emailCategorization.py: The main program, this is the program which needs to be executed.

How to run this project:
1] Setting up the environment. 
Requires Python 3+ Libraries required: pandas numpy scikit-learn timeit (Alternatively use the Anaconda Data Science platform) 
2] Run the script emailCategorization.py 
Expected time to complete ~15min

The output of this experiment ois calculated in terms of hamming loss. The Hamming loss is the fraction of labels that are incorrectly predicted. More about Hamming loss can be found here <a href="https://scikit-learn.org/stable/modules/generated/sklearn.metrics.hamming_loss.html#targetText=The%20Hamming%20loss%20is%20the%20fraction%20of%20labels%20that%20are%20incorrectly%20predicted">here </a>
