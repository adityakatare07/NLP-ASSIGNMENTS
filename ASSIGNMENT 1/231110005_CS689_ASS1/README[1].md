Run the files using Jupyter on Anaconda
Installations Required:
 1.conda install sentencepiece
 2.conda install protobuf
 3.conda install transformer

Files to be uploaded to Jupyter:
corpus .txt


File Descriptions:
corpus .txt is corpus provided

Q1-Q2 same code for both the question i have not printed unicode correction and syllables becuse i am running on whole corpus unicode correction is saved in list brr  and syllables is saved in list crr top frequency are printed.
Q3 is already submitted on the given website
Q4 Not able to run on indicbert(it is taking very much time) model output for indicbert maxlen=2000 is for small data that i used to test earlier this is only for indicbert model
Q5 I have uploaded required data from question 3 manually in tokenizer_outputs and sentences list
Q6 cs 689.pdf - Contains answer for Q6

Constraints:
IndicBERT model is not given the whole corpus as it took too long to tokenize.

ASSUMPTION:
I have conidered unicode correction words like "चाँद" as " च + आ + अं + द + अ "