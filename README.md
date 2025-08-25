Explanation in easy way:- Download the ML-sms.ipynb file and run it. Then include your file path in it like mine was sms.txt in this repository for example it will give all the output written in the description down explaind 
Then it will give and output the by name you will input of the file in it.
Spam Message Detection using Machine Learning:-
This project is a Spam SMS Detector built with Python and machine learning. It trains a model on SMS messages to classify them as spam or ham (not spam).
It uses NLTK for text preprocessing (tokenization, stopword removal, stemming) and Multinomial Naive Bayes with TF-IDF vectorization for classification.

How to Use:-
Prepare your dataset
Create a file named sms.txt in the project directory.
The file should be a tab-separated file with two columns:

spam   Congratulations! You have won $1000.
ham    Hi, how are you doing today?
ham    Let’s catch up tomorrow.
spam   Free entry in 2 a weekly competition...

The first column is the label (spam/ham).
The second column is the message text.
Run the program
Open a terminal in your project folder and run:
python spam_detector.py

Choose input file
The program will ask for a file path.
Press Enter to use the default file (sms.txt).
Or enter another file path (CSV/TXT/TSV supported).

View results
The script will display:
All detected spam messages with spam probability.
Summary (total messages, number of spam/ham, spam rate).
Save results (optional)
After detection, you can choose to save results to a CSV file (default: spam_results.csv).
The file will contain:
label, message, prediction, spam_probability
ham, Hi how are you, ham, 0.02
spam, Congratulations you won, spam, 0.95

⚙️ Features

✅ Preprocesses text (lowercasing, punctuation removal, stopwords removal, stemming).
✅ Supports different input file formats (CSV, TXT, TSV).
✅ Trains a new model if one isn’t provided.
✅ Shows spam probability for each message.
✅ Option to save results in a CSV file.
