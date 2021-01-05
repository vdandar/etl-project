# etl-project
Hi All,
  I started drafting our code tonight. I got through initial steps of reading in and basic cleanup. There is one snag we need to work on tmw: the one file has 153 countries (Happiness Survey data) and the other has 214 (the World Bank data). I examined these in excel and there are a number of countries from the World Bank file that need deleting -- most of these are island nations that are affiliated with other countries. There are also a few countries in the world bank file (14) that need to be renamed to match the Happiness Survey file. Since the data file was small, I could easily identify the common 149 countries between the two files and what needs deletion and updating.  (You can see in the excel files those needing deletion are in yellow and red text indicates a rename needed) However, I think we should demonstrate a way to do this via python instead of just deleting them in excel first? 
  
My one idea for this was possibly creating a small "test" dataframe with the country name and index from each file and parsing the country names to the first 5 or so characters and then try a Boolean test? Then we could "identify" the records that need editing or deletion? Or maybe just in general a comparison between the two country names columns? If you have any time to research before we meet tomorrow, it would be greatly appreciated!!!
Thanks much,
 V
