# Keegan-s_card_collections

## Background
My nerdy younger brother, Keegan, collects Magic the Gathering Cards. He talks about them incessantly. As hard as I try to focus and listen, I quickly get bored and tune out. 
In effort to show him I care about his interests, while not being particularly interested in Magic Cards myself, I offered to database his collections. My hope is that this projects brings us closer to understanding each other and how we approach things differently. It's a win-win-win situation. He gets his collection cataloged and databased. I get valuable practice working on data assembly, cleaning, building databases, web scraping, HTML, and JavaScript. We get quality time together. Also, I do believe this effort puts me in running for best sister ever....forever. 

![Header_image](Images/Header_image.jpeg)

## Methods
### Data entry

We reviewed the characteristics of each card and made a simple excel spreadsheet to start collecting the data. 

We quickly were confronted with some challenges. 
1. Not all cards have all the fields we created resulting in NULL entries. 
2. One card can belong to many expansion packs creating a one-to-many relationship

### Data cleaning
I plan to upload the datasheets to Jupyter Notebook and use Pandas to combine and clean the data.  

### Data Scraping
* To resolve the expansion pack conumdrum, I tasked keegan with finding a website that listed all the cards available in each expansion pack so I can scrape the site with Flask or Django and then "match" the cards to their respective expansion sets. Note: this may require visiting multiple sites as there are a lot of expansion packs, apparently.  

### Databasing
There will be multiple datasets to compile into a relational database. 
* Keegan's Collected Cards
* Cards belonging to Expanison packs

## Product
I will build a website using HTML where Keeg can search his cards through the database

## Future
I'm going to create a "form", most likely with JavaScript, where Keegan can enter the information for cards he may acquire in the future into the database. It will have dropdown menus for series type, mana, expansion pack, and open fields for Abilities, flavor text, Subtype, Name, as well as a section for notes. 

One day, we hope to digitize his collections by imaging each card and attaching the image to its digital record. 
