# Tweet Classification with BART Large MNLI 
Narrative and sentiment classification of UK tweets scraped using the word 'immigrant' (November 2021 - July 2021) 
and the correlation between the economic variables such as consumer price index (CPI), consumer prices index including owner occupiers' housing costs (CPIH),
owner occupiers' housing costs (OOH) and seasonally adjusted total unemployment rate (UR). 
****
**Contains:**
1. **Narrative classification** using [BART Large MNLI Model](https://huggingface.co/facebook/bart-large-mnli) using the labels: *Economy, Politics, Human Trafficking, Citizenship, Border Crossing, Illegal Migrants and Human Rights*, which have been intuitively decided by running multiple GSDMM models on the data. 
2. **Sentiment analysis** using [BART Large MNLI Model](https://huggingface.co/facebook/bart-large-mnli) using the labels: *Anti-Immigrant Sentiment* or *Pro-Immigrant Sentiment*. 
3. Daily overall sentiment score by multiplying the sentiment scores by minus one and getting a daily sentiment mean. 
4. Daily average sentiment score for each narrative by grouping every narrative and applying the same method above. 
5. Performing pairwise correlation between the 'Economy' daily average sentiment score and the economic variables. 

Does not contain the dataset for ethical purposes. 
****
