# WhatsApp-Chat-Analyzer
<br>
Author : Suryayan Mukhopadhyay
<br><br>
-----ABOUT THE PROJECT-----<br>
The WhatsApp Chat Analyzer project aims to develop a tool using Python
and machine learning techniques to analyze WhatsApp chat data.<br>
The tool preprocesses the chat data, extracts insights, and visualizes
various statistics such as message frequency, most active users, common
words, and emoji usage.
<br><br>
1. Preprocessor (`preprocessor.py`) :
This file contains functions for preprocessing the WhatsApp chat data. It
extracts information such as user messages, dates, and other metadata from the
raw chat data. Key functionalities include:<br>
- Parsing messages and dates from the raw chat data.<br>
- Cleaning and structuring the data into a Pandas DataFrame.<br>
- Extracting user names and messages, and performing data transformation and
feature engineering.<br>
- Generating additional features like message counts by date, hour, and day.<br><br>

2. Helper Functions (`helper.py`):
The `helper.py` file contains various functions to assist in analyzing the
preprocessed chat data. These functions include:<br>
- Calculating statistics such as the total number of messages, words, media
shared, and links shared.<br>
- Creating visualizations like word clouds, bar plots for the most common
words, and emoji analysis.<br>
- Generating timeline visualizations for monthly and daily activity.<br>
- Analyzing activity patterns through maps and heatmaps.<br>
- Identifying the busiest users in the group.<br><br>

3. Application (`app.py`):
The `app.py` file utilizes Streamlit to create an interactive web application for
the WhatsApp Chat Analyzer. It allows users to upload their chat data, select
specific users for analysis, and view various statistics and visualizations based on
the selected parameters. The application provides insights into user activity,
word usage, emoji usage, and overall chat trends.
