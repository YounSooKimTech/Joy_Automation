# Joy_Automation
![NLP](https://img.shields.io/badge/NLP-Natural%20Language%20Processing-brightgreen)
![Languages](https://img.shields.io/badge/Languages-Multilingual-blue)
![Web Scraping](https://img.shields.io/badge/Web%20Scraping-Enabled-green)
![Data Visualization](https://img.shields.io/badge/Data%20Visualization-FFA500?style=for-the-badge)
![Task Automation](https://img.shields.io/badge/Task%20Automation-4B0082?style=for-the-badge)
![Google Form](https://img.shields.io/badge/Google%20Form-4285F4?style=for-the-badge&logo=google&logoColor=white)


## 📊 Gardner's Multiple Intelligence Theory Questionnaire & Data Visualization
This project revolves around a simplified questionnaire based on Gardner's multiple intelligence theory. When individuals answer these questions, the data is collected and stored in a Google Form response spreadsheet.

### Data Collection
- A Google Form is used to gather responses from participants.
- Responses are stored in a Google Sheets spreadsheet for easy data management.

### Data Visualization
- The collected data is processed and analyzed to create spider charts.
- Spider charts visually compare an individual's strengths and weaknesses relative to the overall average.
- The title of each spider chart is generated based on the user's name input.
- PNG files of these charts are saved under the user's email address.

### Email Notification
- As a final step, the project automatically sends the generated PNG chart as an email attachment to each participant's email address.

This system allows for a comprehensive assessment of individual strengths and weaknesses, providing a personalized visualization of the results.
If you have any questions or feedback about the project, please don't hesitate to reach out by yk2949@columbia.edu


----------------------------------------

## Automatic Language detection and translation with Google Translator


### Overview
One of the significant challenges in Natural Language Processing (NLP) is dealing with text data in various languages. This code snippet demonstrates how to detect the language used in text data and translate it into English using Google Translator.

### Packages
   Ensure you have the necessary Python packages installed. You can install them using pip:
   This code needs pandas, langdetect, spacy
   
### Important Notes
   - **Language Detection Options**: In this code, we've showcased both `langdetect` and `spaCy` for language detection. You have the flexibility to choose the one that suits your needs best.
   -  **Verification of Language Detection**: After obtaining language detection results, it's a recommended practice to verify whether the detected language is correctly categorized. Ensuring accurate language identification is essential for reliable translations.
   -  **Universal Translation to English**: The code provided in the translation section demonstrates the translation of text in various languages into English. This enables you to work with a standardized language (English) for downstream Natural Language Processing (NLP) tasks.


------------------------------
## predoc.org web scrapping

### Introduction

This Python script automates the task of scraping RA (Research Assistant) opportunities from the [predoc.org](https://predoc.org) website. It generates an Excel file with two sheets: one for "predoc.opportunities" and the other for "predoc.ra-opportunities." The dataset automatically filters out opportunities with application deadlines that have already passed based on today's date.

### Packages
   Ensure you have the necessary Python packages installed. You can install them using pip:
   This code needs pandas, numpy, BeautifulSoup, requests, and datetime

###  Important Notes
- Make sure to check the [predoc.org](https://predoc.org) website regularly as the script is designed to work based on certain assumptions:
- The website follows a consistent format: the text and hyperlinks for opportunities should be in a specific format for the script to capture them.
- The script filters out opportunities with application deadlines that have already passed to provide you with up-to-date information.

### Good Luck!
Feel free to customize and enhance this script to meet your specific needs. Happy scraping!
Also, if you find an error, please let me know too. 
