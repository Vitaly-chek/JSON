[HW_2 : Terminal. Format : XML](https://github.com/Vitaly-chek/XML)

[HW_2 : Terminal. Format : TXT](https://github.com/Vitaly-chek/TXT)

[HW_1 : Terminal](https://github.com/Vitaly-chek/Terminal)

[HW_1 : Git](https://github.com/Vitaly-chek/Git)

---

# HW_2 : JSON

1. Create an external repository called JSON;

2. Clone the JSON repository to the local computer - `git clone URL`;
 
3. Inside the local JSON create a file “new.json” - `touch new.json`;
 
4. Add a file under the git - `git add new.json`; 
 
5. Commit the file - `git commit -m "new file"`;
 
6. Push the file to an external GitHub repository - `git push`;
 
7. Edit the content of the “new.json” file - write information about yourself (name, age, number of pets, 
    future desired salary). Write everything in JSON format:

```
{
	"info":
	{
		"about_me":
			{
				"name" : "Vitaly",
				"lastname" : "Krivoruchek",
				"age" : 23,
				"pets" : 3
			},

		"work":
			{
				"position" : "QA Engineer",
				"salary" : 600,
				"currency" : "USD"
			}
	}
}	
```

8. Push changes to an external repository - `git commit -am "updated file" / git push`;
 
9. Create file preferences.json - `touch preferences.jsone`;
 
10. In the preferences.json file, add information about your preferences (Favorite movie, favorite series, 
    favorite food, favorite season, side you would like to visit) in JSON format:

```
{
    "preference":
        {
            "favorite_movie" : "The Wolf of Wall Street",
            "favorite_series" : "The 100",
            "favorite_food":
                [
                    "Okroshka",
                    "Fried potatoes"
                ],

            "favorite_season":
                [
                    "Summer",
                    "Autumn"
                ],

            "favorite_countries":
                [
                    "Switzerland",
                    "Canada"
                ]
        }
}
```
 
11. Create a skills.json file, add information about the skills that will be studied in the course in JSON format - `touch skils.json`:

```
{
    "skills":
        {
            "1" : "Basic theory",
            "2" : "What is client-server architecture",
            "3" : "HTTP Server request methods",
            "4" : "HTTP server response codes",
            "5" : "HTTP request and response structures",
            "6" : "What is JSON, XML. Their structure",
            "7" : "API testing via Postman (JS, API autotests)",
            "8" : "Removing and reading logs from an external server",
            "9" : "Sniffing http web traffic via Charles and Fiddler",
            "10" : "Dev Tools of web browsers (Google Chrome, FireFox)",
            "11" : "VPN. (How it works, why you need it, how to use it, tool options)",
            "12" : "Mobile testing",
            "13" : "iOS feature, android, guidelines",
            "14" : "Building iOS apps with XCode",
            "15" : "Building Android apps with Android Studio",
            "16" : "ADB (android device management)",
            "17" : "Proxy and vpn setup on iOS and Android",
            "18" : "Interception (sniffing) mobile traffic via Charles and Fiddler on iOS and Android",
            "19" : "Linux command line (terminal) (copy, create, view, move files on non-GUI servers)",
            "20" : "Basic bash scripting, automation of routine tasks on the server",
            "21" : "Access to remote servers",
            "22" : "SQL Basics (Create, Delete, Drop, Insert Into, Select, From, Where, Join)",
            "23" : "Postgres database (installation, configuration and use)",
            "24" : "Redis non-relational database (installation, configuration and use)",
            "25" : "Load testing in Jmeter",
            "26" : "Scrum development methodology"
        }
}
```

12. Send 2 files at once to an external repository - `git add . / git commit -am "new 2 files" / git push`;
 
13. On the web interface, create a bug_report.json file;
 
14. Make Commit changes (save) changes on the web interface;
 
15. Modify the bug_report.json file on the web interface, add a bug report in JSON format:

```
{
	"bug_report":
		{
			"project" : "Notes",
			"version" : "1.3",
			"id" : "№5",
			"summary" : "When clicking on the 'A to Z' filtering button on the main page of the application, chaotic filtering of lists occurs",
			"step_to_reproduce":
				[
					"1. Open the 'Notes' app",
					"2. Create 15 lists that will start accordingly (A, a, D, 3, :, U, u, Ш, ш, 5, @, Ї, ї, -, d)",
					"3. On the main page of the application, click on the filter button 'A to Z'"
				],
			"actual_result" : "Lists are sorted randomly",
			"expected_result": 
				[
					"The lists are sorted in order: symbols, numbers, Latin letters (upper case first), Cyrillic letters (upper case first)",
					"Correct order : (-, :, @, 3, 5, А, а, D, d, U, u, Ї, ї, Ш, ш)"
				],
			"severity" : "Minor",
			"priority" : "Normal",
			"status" : "New",
			"environment" : "IPhone 7 Plus, version 15.4.1",
			"author" : "Vitaly",
			"assignee" : "Ivan",
		}
}
```
 
16. Make Commit changes (save) changes on the web interface;
 
17. Synchronize external and local JSON repository - `git pull`.
