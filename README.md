# Nashville_City_Cemetery_Tableau
## Overview
This is the second itteration of an early project I did in Excel. The original can be found [here](https://github.com/jraiaromano/Nashville_City_Cemetery). In that project I was asked to comb through the very un-tidy Nashville City Cemetery burual records to pull out any interesting facts. 
In this project, I was required to produce a Tableau dashboard or story that drilled down into some part of the City Cemetery data. I chose to focus on the demographics and surrounding impact of the diseases and other causes of death that claimed the lives of those buried in the Cemetery. 
## Project Takeaways
This was a really interesting dataset to work with in Tableau because it was still really... messy. We're talking misspellings and typos throwing off statistics (because "neh-mony" doesn't get counted as "pneumonia" in the count of causes of death) left and right. None of which Tableau can really deal with, as there are virtually no data transformation tools. This gave me a really great idea of precisely what Tableau can and cannot do. 

## The Pitch
Choose a dataset you are familiar with and use Tableau to create a dashboard to tell a new data story, one you have not told before. 

## The Data
I am familiar with this set since I have been in love with it from the first time I laid eyes on it. It's beautifully untidy. It's full of typos, misspellings, null fields, and wacky now-dead traditions and conventions. It is challenging to make sense of, but filled with treasure.

## Approach to the Problem
As mentioned above, I very rapidly ran into the issue of not being able to address data errors directly in Tableau. I probably started and restarted this dashboard 5 or 6 times, building it up from scratch each time. Next time I will know to get all that stuff done first. I think I was optomistic about Tableau's capabilities at first. It does have a lot of features... but none that helped me clean this data up.
Once I strategically cleaned my data, fixing misspellings/typos and standardizing things like sex codes ("female" was 'f', 'F', 'Fe', 'W', 'Woman', 'woman', and 'd'), I was able to create some charts. I went with a bunch of bubble chart because the format, to me, was suggestive of petri dishes, something I found thematically appropriate when dealing predominatly with diseases. 
![image](https://user-images.githubusercontent.com/52726447/71549053-b8b87000-297c-11ea-8084-a82095c743aa.png)
Selecting a cause of death from the left petri dish will give further information on the victims of that cause, including sex percentage, average age, and months in which those deaths ocurred. Some deaths are seasonal or predominatly affected certain populations, either by age or by sex. I did this using dashboard actions, a very useful and exciting tool. 
![image](https://user-images.githubusercontent.com/52726447/71549127-e81bac80-297d-11ea-9596-0f6e8f4097d2.png)


To experience the full dashboard, please visit it on [Tableau Public](https://public.tableau.com/profile/julia5722#!/vizhome/NashvilleCityCemetery/Dashboard1?publish=yes).

**If you want to see more of this data, here is a [link](https://github.com/jraiaromano/Nashville_City_Cemetery) to my Excel project using this dataset to create marketing materials.*