# spam-email-classifier using python

## Description:
this mini project classifies emails as spams or not spams using python

## Used Technology:
python programing

## Features:
detects spams 
text based classification
simple and beginner friendly


##simple python program for identifying spam email:
program:
# List of common spam words:
spam_words = [
    "win", "free", "money", "cash", "prize",
    "offer", "click", "buy now", "urgent",
    "lottery", "congratulations"
]

message = input("Enter your email message: ")

message = message.lower()

spam_score = 0

for word in spam_words:
    if word in message:
        spam_score += 1

if spam_score > 0:
    print("This message is SPAM")
else:
    print("This message is NOT SPAM")


    #Saikumar lonare
    Department of BS-MS
