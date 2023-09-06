# Hate Speech Detection in Hindi

## About The Project

Hate speech is prevalent on various online platforms, including social media, comments sections, blogs, and biased online publications. Despite the existence of profanity filters, they often only address explicit obscenities and swear words. Much of hate speech comprises veiled attacks and the use of seemingly innocuous words to target individuals or groups. Detecting and categorizing such hate speech requires context and knowledge of the topic under discussion, which exceeds the capabilities of rule-based algorithms. However, this project aims to achieve high precision in detecting and categorizing hate speech in Hindi, differentiating between weakly and strongly hateful content.

We refer to the paper linked [here](https://gvpress.com/journals/IJMUE/vol10_no4/21.pdf) as the foundation for building a tool that analyzes a Hindi corpus (a collection of tweets, specifically - accessible [here](https://github.com/mohit19014/Hindi-Hostility-Detection-CONSTRAINT-2021/blob/main/Dataset/valid.csv)) to identify hate speech. The tool categorizes tweets as "weakly hateful," "strongly hateful," or "non-hateful" based on the hate content present.

## Built With

* Python
* [Hindi WordNet](https://www.cfilt.iitb.ac.in/wordnet/webhwn/wn.php?nomorph=true&hwd=%E0%A4%AE%E0%A4%BE%E0%A4%B0)
* [SentiWordNet](https://amitavadas.com/sentiwordnet.php)

## Usage

To use this project:

1. Run the [notebook](https://github.com/mithleshupadhyay/Hindi-Hate-Speech-Detection/blob/master/Hate_Speech_Detection.ipynb).
2. Navigate to the Data section and update the file name with your dataset.
3. The results will be saved in the `results.csv` file.


Author: Mithlesh Upadhyay
