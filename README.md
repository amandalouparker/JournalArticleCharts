# JournalArticleCharts
Customised matplotlib charts for journal article count data



This article takes a look at the field of psychology's involvement in human computer interaction (HCI) research through customised charts of article counts and research area using pythons plotting library 'matplotlib'.


**Psychology and digital interaction**

The advance of digital technology into our lives has led to sometimes concerning outcomes for the wellbeing of certain individuals and groups; from fake news and the use social media by a foreign country to influence an election to incidences of bullying and harassment and even murder - it seems timely that fields in the psychological and social sciences would be becoming more involved in studying how humans interact with computers - a field known as "Human Computer Interaction" or HCI for short. 

Increasingly commercialised & democratised channels of information exchange have done away with the level of authentication associated with more traditional, socially-subsidised publishing roles such as journalists and researchers. Rather than lamenting changing times, this might pose an opportunity to better understand how software design shapes and moulds individual and community behaviour, belief, health and wellbeing, as well as the possibility for these old practitioner roles to evolve into more strategic or systems-design based ones.

With these ideas in mind, I collected research article statistics from the Web of Science database - results downloaded were article counts per year (and for research area) returned for the topic keyword "Human Computer Interaction", as well as 'Interaction Design' and 'Human Factors' topics for comparison. I also wanted to use this as an example of charting publication counts for a research topic over time and by research areas (or subtopics) more generally.

**HCI Articles on the rise**

This first chart shows the overall number of HCI topic articles increasing since 1980. There is a steady incline, with some incomplete results for the current year. 

![All HCI papers](https://raw.githubusercontent.com/amandalouparker/JournalArticleCharts/master/images/HCI_bar-total.png)


**Human Computer Interaction research areas**

The second chart breaks these article counts into the research areas they were published under. Computer Science takes out the lead with 36.2% of the articles in this research area. Next was Engineering at 19.7% followed by Psychology at 3.9%, which tops out the areas under 5% of the papers. 


![Image Alt Text](https://raw.githubusercontent.com/amandalouparker/JournalArticleCharts/master/modified-images/HCI_piechart.png)



**Top 3 HCI research areas across time**

![Papers per top research areas across time](https://raw.githubusercontent.com/amandalouparker/JournalArticleCharts/master/images/HCI_bar-areas.png)


**Research areas - as a proportion of total articles**

Proportion of articles for top 3 research area (CS, Engineering, Psych.) in a stacked area chart. There is a clear gain in the proportion of CS and Engineering articles over psychology ones starting around the launch year of the first Apple Macintosh computer. 

![Stacked area chart of the proportion of papers from each top area](https://raw.githubusercontent.com/amandalouparker/JournalArticleCharts/master/modified-images/HCI_stacked.png)


**'Human Factors' keyword**

In psychology the term 'Human Factors' is often interchanged for HCI. Checking the data on this topic results in an elevated number of psychology articles, however the trend over time is similar, with little to no growth in article count compared to the top 2 research areas. The top areas Computer Science and Engineering have swapped their #1 and #2 positions indicating the "Human Factors" topic is less likely to be used for CS articles than Engineering ones. 

![Image Alt Text](https://raw.githubusercontent.com/amandalouparker/JournalArticleCharts/master/modified-images/HumanFactors_piechart.png)

Human Factors articles showed a similar trend to HCI ones, with little to no growth for psychology articles relative to the overall growing trend. 

![Image Alt Text](https://raw.githubusercontent.com/amandalouparker/JournalArticleCharts/master/images/HumanFactors_line.png)

**'Human Factors' research areas**

The stacked area chart for the 'Human Factors' keyword shows the same trend as the HCI keyword. Something is going on here, psychology research in Human Factors and HCI has remained almost static compared to steady growth in the Engineering and Computer Sciences. This might be because the results mirroe the relative size of the research population in those fields. Or it could be general drift away from HCI/Human Factors research in the psychology community (or vice versa, an increased on in Engineering and CS). The shift of the study of computer human experience into the hands of design teams working for private companies and corporations might be another factor. 

![Stacked area chart of the proportion of papers from each top area](https://raw.githubusercontent.com/amandalouparker/JournalArticleCharts/master/modified-images/HumanFactors_stacked.png)


**Significant events in HCI**

The slow drop-off in psychology HCI articles (relative to the growing trend in Comp Sci and Engineering ones) started around 1990, around the time of the rise of apple. I think this marked the start of an era of companies owning the design of systems, including their impact on individual and group psychology, as Apple has done so well to capture peoples time and money. I'm not saying it's a bad thing that companies can build systems that shape and change our humanity, just that this sort of design knowledge could also be used right now to design and govern systems for greater social benefit in cases with less monetary incentive for the companies to do it - i.e. the current problems of fake news and online abuse. 



