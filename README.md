# Athletic Sales Analysis
HW5

## Overview
Sales data from 2020 and 2021 for certain regions and retailers was provided. Using this data, the instruction was to combine two .csv files, clean the data and answer specific questions. The Module 5 Challenge instructions provided an example of what the output should look like for each set of questions. This was very helpful and appreciated.

The relevant file for this assignment is athletic_sales_analysis_starter_code.ipynb. There are two .csv files that were provided.

## Issue - 'inner join'
This may just be my limited understanding, but in the instructions it said "Combine the two DataFrames by the rows using an inner join, and reset the index." I thought that when the term 'inner join' was used that the 'merge' function was the best choice. However, when using the 'merge' function, all the columns were getting an _x or _y version since all the columns were the same. After several attempts to use the 'merge' function, I checked with the Xpert Learning Assistand and the AskBCS Learning Assistant and received conflicting responses. Ultimately I used the 'concat' with an inner join and that seemed to produce the best results.

## Support
I have been using Tabnine and Chatgpt most of the time when getting stuck or needing to get something explained to me. I did use the Xpert Learning Assistant for some questions and the AskBCS Learning Assistant too. Last week I was on vacation so I did not participate in office hours or in discussion with other students.

I did search for answers on stackoverflow. However, I have not had much luck in finding relevant responses. I need to spend some more time figuring out how to limit the responses to my specific question.
