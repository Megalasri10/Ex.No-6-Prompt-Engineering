Ex.No.6 Development of Python Code Compatible with Multiple AI Tools

Aim: 

Write and implement Python code that integrates with multiple AI tools to automate the task of interacting with APIs, comparing outputs, and generating actionable insights with Multiple AI Tools.

Explanation:

Develop a python code that integrates multiple AI tool by interacting with their APIs.
Compare outputs from different APIs.
Analyze the response and the Output.

The aim is to understand how to request help from AI tools for tasks like writing Python code, integrating with APIs, comparing outputs, and generating actionable insights.

Program:

Case 1:
```
from nltk.sentiment import SentimentIntensityAnalyzer
import nltk
nltk.download('vader_lexicon')
generated_text='this smartphone offer outstanding battery life and an intelligence AI camera that caputure stunning photos.'
print("Generated Review:\n")
print(generated_text)
sia=SentimentIntensityAnalyzer()
sentiment=sia.polarity_scores(generated_text)
print("\nSentiment Analysis:")
print(sentiment)
if sentiment['compound']>0:
  print("\nInsight:The reviem is positive and suitable for marketing promotion.")
else:
  print("\nInsight:The review tone is negative or neutral.")
```

Case 2:
```
from nltk.sentiment import SentimentIntensityAnalyzer
import nltk
nltk.download('vader_lexicon')
generated_text='this smartphone offer outstanding battery life and an intelligence AI camera that caputure stunning photos.'
print("Generated Review:\n")
print(generated_text)
sia=SentimentIntensityAnalyzer()
sentiment=sia.polarity_scores(generated_text)
print("\nSentiment Analysis:")
print(sentiment)
if sentiment['compound']<0:
  print("\nInsight:The reviem is positive and suitable for marketing promotion.")
else:
  print("\nInsight:The review tone is negative or neutral.")
```
Output:

Case 1:
<img width="1148" height="231" alt="image" src="https://github.com/user-attachments/assets/1f85248a-c87a-4539-9d3f-3891a5090c64" />
Case 2:
<img width="1317" height="236" alt="image" src="https://github.com/user-attachments/assets/9ca04fb3-3d20-4e22-a8f4-81f898141192" />

Result: 
 Thus,the implement Python code that integrates with multiple AI tools to automate the task of
interacting with APIs, comparing outputs, and generating actionable insights with Multiple AI Tools.
