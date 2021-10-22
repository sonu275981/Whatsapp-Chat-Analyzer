
# WhatsApp-Analyzer

A python-based web app project to Analyze and Visualize your WhatsApp group chats. The analysis includes most active users, most active date, most active time, top 5 users, analysis of chat on any date, etc.
Link :- https://whatsappchatanalyzerr.herokuapp.com/ 

### All you need to do:

- Export your WhatsApp conversation to text file

- Upload it to analyzer

- View your analysis on the dashboard

### Known Issues:
- Please use only 24 hour Time Format WhatsApp chats.
- There’s no way that it will work for everyone because I’ve found that depending on your OS and version of Whatsapp, the format of text file lines varies wildly. I’m sorry if it doesn’t work for you.

### Tech:
WhatsApp-Analyzer uses a number of open source projects to work properly


 - [STREAMLIT](https://streamlit.io/) - open-source app framework that turns data scripts into shareable web apps in minutes.
 - [Pandas](https://pandas.pydata.org/) - pandas is an open source, library providing high-performance, easy-to-use data structures and data analysis tools for the Python
 - [Matplotlib](https://matplotlib.org/) - is a plotting library for the Python programming language and its numerical mathematics extension NumPy.
 - [Urlextract](https://urlextract.readthedocs.io/en/latest/urlextract.html) - URLExtract is python class for collecting (extracting) URLs from given text based on locating TLD.
 - [WordCloud](https://in.mathworks.com/help/textanalytics/ref/ldamodel.wordcloud.html) - visual representations of words that give greater prominence to words that appear more frequently.
- [Emoji](https://pypi.org/project/emoji/) - Emoji for Python.

  
## Installation

You need Python 3.6 and above, its dependency packages, flask and pandas installed globally:

```bash
 $ git clone https://github.com/sonu275981/Whatsapp-Chat-Analyzer.git Whatsapp-Chat-Analyzer
 $ cd my-project
 $ make run
```

Service will be running on port 8501 - http://localhost:8501/    
## License

[MIT](https://choosealicense.com/licenses/mit/)

  
