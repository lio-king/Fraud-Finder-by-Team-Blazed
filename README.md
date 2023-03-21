# Fraud-Finder-by-Team-Blazed

Here , we select a problem statement : " Make tool for fraud detection "
our basic idea is to make it , in three phase , in each phase we have three model those are :
   1. Spam-mail , 
   2. Malicious url &
   3. Credit card fraud.

Our model is based on real time working.

*1. Spam mail :
In spam mail we use natural processing language beacuse we are using neural networks.
the basic idea behind that is to , extract statements from emails and then check their signature , if 
there signature is matched, more than 50 % then it is fraudulent statement and our model notify
the client or user .

link of our project : https://colab.research.google.com/drive/1Yw5jEEPhoU8nM221wFnYj9Mo-xIuOUc4?usp=sharing#scrollTo=qgcM81hCmuQN

*2. Malicious url
our model works on idea to notify user ,when they click or even use some malicious website , or safe website , they will 
notiied:
in this model we are using four classifier such as phishing , safe , defacement and malware.
here, we are random forest algorithem.
urls = ['titaniumcorporate.co.za','en.wikipedia.org/wiki/North_Dakota']
as you see here , we only two website  in which model should find out which website is malicious or dafe.

link of our project : https://colab.research.google.com/drive/18usPUInA1OHK0IDaxL4SmH5-5hQWvjQ1?usp=sharing#scrollTo=GreQKlCzI88l

*3. Credit card 
As per our research only 1 % of transactions are fraud out of 100 % and the reaming 99 % are real transactions.
this highy unblance data .
checking the class distribution to the class of variable we going to use.
here , we are using knn algorithm.

if gives one for fraud detected or 0 for real transaction.   

link of our project : https://colab.research.google.com/drive/1fI-qK6PRTWM13dx_KBQuPxDTRG-tWolN?authuser=4#scrollTo=242ocGOhI8PZ&uniqifier=1
