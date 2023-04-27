# GIT Homework 1 "TXT"

1. Create an external repository named TXT.  
```   
Go to the "Repositories" tab, then ckick "New", in the "Repository name *" enter repository name and click "Create repository".   
```

2. Clone TXT repository to local machine.  
`git clone git@github.com:AlekseiRbo/TXT.git` 

3. Inside the local TXT create a “new.txt” file.  
`touch new.txt`

4. Add file under git.  
`git add .`

5. Commit file.  
`git commit -m "Add new.txt"`

6. Push file to external GitHub repository.  
`git push`  

7. Edit the content of the “new.txt” file - write information about yourself (full name, age, number of pets, future desired salary). Write everything in TXT format.  
`vim new.txt`  
```
	"user_name": "Riaboshapko Aleksei",
	"user_age": 28,
	"user_animal": 0,
	"user_salary": 1000
```
8. Push changes to an external repository.  
`git commit -am "Add diff new.txt`  
`git push`  

9. Create preferences.txt file  
`touch preferences.txt`  

10. In the preferences.txt file, add information about your preferences (Favorite movie, favorite series, favorite food, favorite season, side you would like to visit) in TXT format.  
`vim preferences.txt`  
```
	"user_favorite_movie": "John Wick",
	"user_favorite_soap_opera": "The Walking Dead",
	"user_favorite_food": "French_meat", "Pork_skewers0",
	"user_favorite_season": "I like all seasons",
	"user_country_to_travel": "Germany"
```  

11. Create a sklls.txt file to add information about the skills that will be studied in the course in TXT format.  
`vim sklls.txt`  
```
	"user_soft_skills":
		"attentiveness", 
		"multitasking", 
		"perseverance", 
		"skill to work in team",
		"and etc"

	"user_hard_skills":
		"Git", 
		"GitHub", 
		"Postman_API", 
		"SQL", 
		"SOAP_API", 
		"and etc"
```  
12. Make a commit in one line.  
`git add . && git commit -am "Create 'preferences.txt' and 'sklls.txt'"`

13.  Send 2 files at once to an external repository.   
`git push`  

14. On the web interface, create a bug_report.json file.  
Click in the repository `Add file` then `Create new file` in field "Name your file..." enter "bug_report.txt"  

15. Make Commit changes (save) changes on the web interface.  
In field "Update README.md" enter ***changes*** then click `Commit changes`  

16. On the web interface, modify the bug_report.txt file, add a bug report in TXT format.  
Go to file "bug_report.txt" click `Edit this file`, insert txt file:  
```
  "ID": "001",
  "Severity": "Medium",
  "Environment": "Devices",
  "Title": "What?Where?When?",
  "Steps": "Steps to reproduce",
  "ER": "Expected Result",
  "AR": "Actual Result",
  "Link": "link",
  "License": "license",
  "Role": "Unregistered, Unauthorized, Authorized, All",
  "Telegram @nick. Bug started": "@_",
  "Telegram @nick. Bug reproduced": "@_",
  "Telegram @nick. Bug didn't reproduce": "@_",
  "Bug didn't reproduce (environment)": "Devices"
```

17. Make Commit changes (save) changes on the web interface.  
In field "Update README.md" enter ***changes*** then click `Commit changes`  

18. Synchronize external and local TXT repository.  
`git pull`
