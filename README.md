# Tweet Influencers
This project is a part of the [Galvanize Alumni Relations](http://glavanize.com) at [Galvanize Datathon 2020 Blog](https://blog.galvanize.com/alumni-datathon-digging-into-the-election/).  Other DSWG projects can be found at the [main GitHub repo](https://github.com/yuchild/galvanize_datathon2020).

#### -- Project Status: [Active]

## Project Intro/Objective
The purpose of this project is use . (Describe the main goals of the project and potential civic impact. Limit to a short paragraph, 3-6 Sentences)

### Partners
* Mathias Darr, Data Scientist and Data Engineer Extraordinaire
* Julia Sokolova, Data Scientist Project Manager Queen Bee
* David Yu, Data Scientist EDA Guru

### Methods Used
* Inferential Statistics
* Machine Learning
* Data Visualization
* Predictive Modeling
* etc.

### Technologies
* Python
* D3
* PostGres, MySql
* Pandas, jupyter
* HTML
* JavaScript
* etc.

## Project Description
(Provide more detailed overview of the project.  Talk a bit about your data sources and what questions and hypothesis you are exploring. What specific data analysis/visualization and modeling work are you using to solve the problem? What blockers and challenges are you facing?  Feel free to number or bullet point things here)

## Needs of this project

- frontend developers
- data exploration/descriptive statistics
- data processing/cleaning
- statistical modeling
- writeup/reporting
- etc. (be as specific as possible)

## Getting Started

1. Clone this repo (for help see this [Readme](https://github.com/yuchild/galvanize_datathon2020/blob/main/README.md)).
2. Raw Data is being kept offline due to size considerations. Do get started do the following:

Data Source: [GitHub Repo link provided @12PM Friday 10/29/2020]

Clone [GitHub Repo link provided @12PM Friday 10/29/2020]

Follow the instructions in the repository to install twarc and tqdm.

Apply for a twitter developer account.

Save api key, save api secret key, save bearer token.

Enter your twitter api information into twarc.

Use a mv command to move the contents of the desired days into a new single directory.

Look inside the cloned repository for the appropriate .txt files containing tweet ids. (ex. cat * >>
file name.txt)

Concatenate those files into one file.

In the terminal, use awk 'NR % 100 == 0' <file.txt> > <result.txt> to systematically sample every

100th tweet id. These are the tweets you will hydrate.

Modify the hydrate.py script in the cloned repository and run the script to rehydrate tweets from your file of tweet ids.

Analyze tweets.

3. Data processing/transformation scripts are being kept [here](https://github.com/yuchild/galvanize_datathon2020/commit/14bf75445630b26fb33ac53e685442f1e6c846e4)
4. etc...

*If your project is well underway and setup is fairly complicated (ie. requires installation of many packages) create another "setup.md" file and link to it here*  

5. Follow setup [instructions](Link to file)

## Featured Notebooks/Analysis/Deliverables
* [Notebook/Markdown/Slide Deck Title](link)
* [Notebook/Markdown/Slide DeckTitle](link)
* [Blog Post](link)


## Contributing Members

**Team Leads (Contacts) : [Julia Sokolova](https://github.com/JuliaSokolova)**

#### Other Members:

|Name     |  Slack Member ID  |
|---------|-----------------|
|[Mathias Darr](https://github.com/MathiasDarr)| U01DGT9BYJE |
|[David](https://github.com/yuchild) | U01DFNWBMNX |

## Contact
* If you haven't joined the Galvanize, [you can do that here](https://www.galvanize.com/).  
* Our slack channel is private because of Datathon rules
* Feel free to contact team leads with any questions or if you are interested in contributing!
