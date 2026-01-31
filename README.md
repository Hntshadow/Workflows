# WORKFLOWS
easy to use and setup n8n worflows
## workflows
1. curl-agent.json
2. indeed-job-scraper.json         
3. remote-job-scraper.json

## overview
1. uses webhook to deploy/execute the **agent**
2. uses combination of [apify]() and [airtable]() to give a **list** of jobs
3. uses [arbeitsamt API]() with google sheet to give a **list** of remote jobs in either in _Europe_ or just _Germany_ 

#### Instruction
- choose and select your workflows
- download or copy the ***JSON*** code
- paste it within ***n8n 1.109 +*** or higher version
- paste your **APIs** and **oAUTHs** ( if present )
- align ur sheets ***google*** or ***airtable*** with headers
- then execute

#### n8n Setup
- Download n8n  
  ***locally*** -  
  ***Docker (recomended)*** -  
  ***WSL*** -  

- sign up and create ur **n8n account community edition**

- click create workflow
- top right near share
```   
click (:)  
click on import from file   
navigate the JSON file
```  
- the workflow should apear

#### APIs 
- use [Apify]() for job scrapers or my ***indeed-job-scraper***
- use github repo [arbietsamt](https://github.com/public-apis/public-apis?tab=readme-ov-file#jobs) or any other APIs avalible there for remote job scraper or my ***remote-job-scraper***
-use [google cloud console]() to use google cloud services like google sheet ,google drive ,google docs etc
- alernativly use [airtable]() for _data sheet_
- use [convex]() for _data base_
-use [open router]() for your custom agent or my ***curl-agent***

### note and disclamer
```
- The older version of n8n might need manual setup  
- n8n nodes might or will need manual API configuration  
- sometimes the workflow may refuse to run  
- n8n workflow will not work if u have reached ur limit   
- n8n working on the cloud will need a different setup  
- the agent above is just a skeleton and needs a webpage to work in an project since it runs in the terminal curl 
```