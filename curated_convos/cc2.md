# Curated Conversation  2
## Why (Not) a Map?
with Jess Cohen-Tanugi on [day 3](../day3.md)  

### Recommended Reading
- [When a single map isn’t enough…](https://www.esri.com/arcgis-blog/products/arcgis-pro/mapping/when-a-single-map-isnt-enough/) by Kenneth Field  
- [What It Looks Like to Reconnect Black Communities Torn Apart by Highways](https://www.bloomberg.com/graphics/2021-urban-highways-infrastructure-racism/) by Rachael Dottle, Laura Bliss and Pablo Robles  
- [The Rhetoric Behind the Coronavirus Propaganda Maps](https://medium.com/nightingale/the-rhetoric-behind-the-coronavirus-propaganda-maps-3cd6ec84aa63) by Mathieu Guglielmino  
- [Mistakes, we’ve drawn a few](https://medium.economist.com/mistakes-weve-drawn-a-few-8cdd8a42d368) by Sarah Leo  

[day 0](../day0.md) | [day 1](../day1.md) | [day 2](../day2.md) | [day 3](../day3.md) | [day 4](../day4.md) | [day 5](../day5.md)  

return to [road map](../road_map.md)

## Activity

Imagine you have the following dataset for a project. Read the descriptions below and consider how you might go about visually exploring this dataset. The questions below are for breakout groups, then we will come together to create some charts, graphs, and maps together. 

### Vesuvius dataset

Some Mt Vesuvius facts:
- Mt Vesuvius is a volcano in Southern Italy, in the outskirts of Naples.
- It's the only volcano to have erupted in mainland Europe in the last hundred years; its last eruption was in March 1944.
- In AD 79 there was a devastating eruption that destroyed Pompeii, described in 2 letters by Pliny the Younger. 
- Vesuvius is regarded as one of the most dangerous volcanos in the world, because... 
  - it's the most densely populated volcanic region in the wold with 3 million people living nearby
  - it has a tendency toward violent, sudden explosions of the Plinian type, named for Pliny's description of Vesuvius
- Harvard connections: In the 1800s, there was a guestbook where people climbing Mt. Vesuvius could sign their names. One particular guestbook, active from 1826-1829, ended up in Houghton Library, where a historian transcribed quite a few lines from the guestbook by hand. This data has since been cleaned even further for easier visualization.

### Data Dictionary

| Variable | Definition | Notes |
| -------- | ---------- | ----- |
| Name | Person who signed guestbook | Sometimes marked "illegible" |
| Date | Date of ascent | Month/Day/Year; year ranges from 1826-1829 |
| Gender | Gender | Male or Female |
| Specific Occupation | Job title, essential | e.g. councillor, chemist, banker, artist, postman, etc. |
| Occupation (general) | General sector of job | e.g. Cleric/Minister of Religion, Politician/Courtier/Functionary, Scientist, etc. |
| Military rank (General) | Rank bucketed somewhat | e.g. Captain, Colonel, Admiral, Lieutenant, Major, etc. |
| Military rank (Specific) | Full military rank | e.g. Imperial Officer, First Class Volunteer, Cadet, etc. There aren't many of these. |
| Social rank (General) | Social rank | e.g. Count/Countess, Prince/Princess, Baronetcy, etc. |
| Social rank (Specific) | Basically, whatever they put before/after name | e.g. Doctor, Chevalier, Priest, Professor, Reverend, Sir, etc. |
| Date of birth | Month/Day/Year | Only available for 200 out of 2300 people |
| Nationality | Country of origin | Tranlated into modern country names for ease of mapping |
| Language | Language in which they signed guestbook |  |
| Party size | How many people ascended with the person signing, including signer |  |
| Number of ascents | Number of times the person goes up Vesuvius in data set |  |
| Origin | Name of origin city or state | |
| Co-ordinates latitude | Latitude of origin city or state | |
| Co-ordinates longitude | Longitude of origin city or state | |

### Group Questions
- Which variables are you most interested in exploring?
- What questions do you have about those variables?
- Can you think of a way/ways to begin to visually answer those questions? E.g., make a map showing how many people climbed Vesuvius from each Nationality; a chart (specify which kind) showing the how many climbers were men vs women, etc. 
