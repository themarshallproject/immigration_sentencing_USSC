### Story ###


A Marshall Project analysis of 17 years of federal prison sentences shows that violations of immigration law already constitute the largest single category of offenses—even more than drug trafficking.

Link: [Sending Even More Immigrants to Prison](https://www.themarshallproject.org/2018/05/20/sending-even-more-immigrants-to-prison), published May 20, 2018.

### Data Sources ###

Each year, the U.S. Sentencing Commission publishes federal sentencing data. In the Appendices section of the [Sourcebook](https://www.ussc.gov/research/sourcebook-2017), there's a breakdown of sentences by U.S. federal district. [These PDFs](https://www.ussc.gov/research/sourcebook/archive) are the basis of the analysis.

We scraped and parsed parts of the data. What is saved as pctimmigchart.csv is data we gathered only on immigration, by these specific sentence buckets:

- Up to 12 Months
- 13-24 Months
- 25-36 Months
- 37-60 Months
- Over 60 Months


### CSV Headers ###

- Year: Data from 2001 to 2017
- District: Abbreviated name of the district
- Immigration: The total number of immigration prison sentences by district. This was created by adding up all the immigration sentencing buckets
- FullName: Full name of the district
- SentenceAdd: The total number of prison sentences, which includes each crime (Robbery, Larcerny, Embezelment, Fraud, Drug Trafficking, Counterfiting, Firearms, Immigration, All Other)
- PCTImmig: Total number of immigration divided by SentenceAdd

### Data Notes ###

This data does not include all convictions, since not everyone gets a prison sentence. Some districts have also not kept track of all the sentencing for their convictions. This means that when adding up of all the sentence length buckets they are not always the same as the Total Receiving population. 

In the years 2004 and 2005, USSC published two sets of data. They account for mid-year changes due to Blakely v. Washington in 2004 and United States v. Booker changes in 2005.

