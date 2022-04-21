# WhatsApp Chat Analysis
## About this project:
- The main goal of this project is to analys the whatsapp chat and represents through charts and visuals.
- Project is live now and deployed on heroku. visit at https://whatsapp-santosh.herokuapp.com/
- This projects can be used for indivisual as well as group chats.
​
## Idea:
1. Created a function that convert WhatsApp chat text file into dataframe with columns name(['date', 'year', 'month', 'day', 'hour', 'minute', 'month_name','day_name', 'user', 'message', 'message_chars'])
​
2. Which Data you will get in this analysis
1. Sum
    - Chat starting date, first entry in chat
    - Chat Ending Date, last entry in chat
    - Total Members in chat, only those who had sent atleat one message
    - Total Messsages, including messages, missed calls, media, links
    - Total Words of Messages, 
    - Total Media File Shared
    - Total Links Shared
    - Total Missed Calls
2. Bar chart of no messages sent by members
3. Bar chart of no messages sent by members with mean line
4. Pie chart with no if messages sent in %
5. Pie chat of Who started and ended chat most of the time
6. WordMap of most 75 words used in chat with stopwords and without stopwords
7. Box Plot of who sent the longest messages
8. Pie chart of most used emoji
9. Sunburt chart of members and thier weekly messages(and yearly,monthly,weekly)
10. Line chart of Daily chat activity(same monthly, yearly) for all and indivisuals
11. Heatmap represents which has occured more on given to features
12. Table of 5 longest message in entire chat
13. Table of 5 Longest message of highest chat happened on a single day
14. Table of all shared links in chat
    
## Charts used to represents data:
    - Bar, Line, Box, WordMap, Sunburst Heatmap
    
## Librabry used
   - **streamlit** : for web application
   - **matplotlib**: for charts 
   - **plotly** : intrective charts
   - **pandas**: for creation of dataframe
   - **PIL**: opening image file 
   - **re** : regular expression
   - **urlextract**: for extracting URL from chat
   - **collections**: for counting each words
   - **wordcloud**: creating wordmap
   - **emoji**: extracting emoji from chat
   - **warnings**: ignore warnings
​
# Code written in pycharm in three files
- **app.py** : main file
- **dataset.py**: for generatig dataset
- **functions.py**: user defined functions as per required
​
#### Project Files link: https://github.com/withusanty/WhatsApp-Chat-Analysis
​
# How to use:
1. To use this webapp first you whatapp chat txt file.
    - You can try your whatsapp of any individuals or groups chat this is 100% SAFE and SECURE, I don't have access to this webapp. So, feel free to use.
    - To export your chat: follow the steps given below:
        - Open your whatsapp in mobile only
        - Open any chat
        - click on three vertical dots (upper right corner)
        - click on More
        - click on Export Chat, proceed with Without Media
        - Now save this file anywhere you want.
        
2. Now, vist at https://whatsapp-santosh.herokuapp.com/
3. Page will look like below
![what2](https://user-images.githubusercontent.com/40932902/164450540-f0700c3e-c0bb-47a7-af01-2b23b71e2782.png)
4. To see details how it works click on plus icon '+', click again '-' to close
5. Browse your file or drang and drop in the file box.
6. Once your file has been uploaded all members name will be visible in dropdown menu,default selecte All, if you want to analys for indivisual member then select that member and click on 'Show Analysis'.


# Some Snapshots:
![what3](https://user-images.githubusercontent.com/40932902/164450748-aeb5c4ae-4030-48bb-a3a8-c63b6e0fde77.png)
![what4](https://user-images.githubusercontent.com/40932902/164450755-c8215423-6c23-47bd-a70c-7369b1533237.png)
![what5](https://user-images.githubusercontent.com/40932902/164450758-3a3b8a72-4651-467d-8b95-d3008c07c519.png)
![what6](https://user-images.githubusercontent.com/40932902/164450759-08a12997-5d06-4f50-9e29-fc272dd28523.png)
![what7](https://user-images.githubusercontent.com/40932902/164450765-38aac503-87e4-4097-a1f2-6cdc89cdac81.png)
![what8](https://user-images.githubusercontent.com/40932902/164450768-d6712ba7-5ecb-4f7b-8d3d-9ebb2c1bc2cf.png)
![what9](https://user-images.githubusercontent.com/40932902/164450771-5ba10e9c-ab57-472a-b8bf-f783271c9056.png)
![what](https://user-images.githubusercontent.com/40932902/164450776-56abca93-6bfe-4ad3-8175-7693be56b7ef.png)
![what2](https://user-images.githubusercontent.com/40932902/164450779-0a41bc80-64ee-41b5-9b52-2282584883fc.png)
