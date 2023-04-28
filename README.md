# JSON
___
###1. Create an external repository called JSON

    click create New Repository
    entered Repository name - JSON
    choose Public repo, add a Readmy file, create repo.
 
###2. Clone JSON repository to local machine
    
    git clone "git clone https://github.com/chelovechek159/JSON.git"

###3. Inside local JSON create file `new.json`
    cd JSON 
    cat > new.json
    "control + c"

###4. Add file under git
    git add new.json

###5. Commit a file
    git commit -m "newJSONFile"

###6. Push file to external GitHub repository
    git push "or u can add file via GitHub (click on button Add file)"

###7. Edit the contents of the `new.json` file - write information about yourself (name, age, number of pets, future desired salary). Everything is written in JSON format
    cat >> new.json 
        {
        "Full name": "*",
        "Age": "*",
        "Number of pets": "*",
        "Future desired salary": "*"
        }
 
###8. Push changes to an external repository
    git add new.json
    git commit -m "text"
    git push -u

###9. Create file `preferences.json`
    json - cat > preferences.json

###10. Add information about your preferences (Favorite movie, favorite series, favorite food, favorite season, country you would like to visit) to the `preferences.json` file in JSON format.
    cat >> preferences.json
        {
            "Favorite movie": "Harry Potter",
            "Favorite series": "Game of Thrones",
            "Favorite food": "bean soup",
            "Favorite season": "Summer",
            "Country you would like to visit": "Japan"
        }

###11. Create a file `skills.json` add information about the skills that will be studied in the course in JSON format
	{
    "Skills": { "1": "Terminal", 
	     	    "2": "SQL",  
		    "3": "GIT",
    	    "4": "Postman",
	            "5": "Client-server architecture"
	            "6": "Mobile testing"
		  }
	}
 
###12. Send 2 files at once to an external repository
    git add .
    git commit -m "text"
    git push

###13. On the web interface, create a file `bug_report.json`
    Add file
    Create new file
###14. Make Commit changes (save) changes on the web interface
    Add changes
    click on the button [Commit changes]
###15. Modify the `bug_report.json` file on the web interface to add a bug report in JSON format
    {
        "ID": 81,
        "Severity": "Minor",
        "Environment": "iPhone 13 (iOS 16.4.1 safari); Xiaomi Redmi Note 7 (Android 10, Chrome 112)",
        "Title": "The images are narrowed when page width is less than 612 px in portrait screen orientation",
        "Steps_to_reproduce": {
            "1": "Navigate to capital.com",
            "2": "Tap on [burger menu]",
            "3": "Tap on menu section [Education]",
            "4": "Tap on menu item [CFD trading guide]",
            "5": "Scroll down to the images",
        },
        "Expected_Result": "Images has normal size in portrait screen orientation",
        "Actual_Result": "Images are narrowed in portrait screen orientation",
        "Link": "https://drive.google.com/file/d/1yGDgoTkzXEMLnPam2g3-2d2ZLRBNLwKF/view?usp=drivesdk",
        "License": "All",
        "Role": "All",
        "Bug_started": "@WiseChel",
        "Bug_reproduced": "@mranolegprivate; @tomkcat; @Olga_username1"
    }

###16. Make Commit changes (save) changes on the web interface
    Add changes
    click on the button [Commit changes]

###17. Synchronize external and local JSON repository 
    git pull

