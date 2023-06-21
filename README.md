
# WhatsApp Group Analysis
This README file describes the process of analyzing a WhatsApp group chat using Python I also created a visualization using powerbi.
<br>
_Here is the PowerBI visualization_
<br>
![PowerBi Visulization](https://github.com/Nwankwo-Nnaemeka/Powerbi_projects/blob/main/Screenshot%20(211).png "WhatsApp Group Analysis")
### The data was collected and cleaned using the following steps:

* The WhatsApp chat was exported as a .txt file.-
* The .txt file was opened in Python and the data was cleaned using regular expressions.
* The cleaned data was saved as a .csv file.
#### The csv file contains the following columns:

<span style="color:green">Authors:</span> The name of the author of each message.
<br>
**Date**: The date and time of each message.
<br>
**Messages_sent**: The number of messages sent by each author.
<br>
**Days of the week**: The day of the week on which each message was sent.
<br>
**Hours of day**: The hour of the day on which each message was sent.
<br>
**Emoji_diction:** A dictionary of the emojis used in the chat, with the number of times each emoji was used.
<br>
**Count_of_emojis_per_message:** The average number of emojis used per message.
<br>
**Types_of_emoji:** The different types of emojis used in the chat.
<br>
**Url_count:** The number of URLs shared in the chat.

# The insights that were gained from the analysis include:

* The most active author EKwutosi
* The most active day of the week Tuesday
* The most active hour of the day was 9.00 pm
* The most popular emoji was 🙏
* A total of 15650 URLs were shared in the chat.

#### The analysis was conducted using Python and the following libraries:

* NumPy
* Pandas
* Matplotlib




