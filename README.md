# JSON
___

### 1. Create an external repository called JSON

    click create New Repository
    entered Repository name - JSON
    choose Public repo, add a Readmy file, create repo.
 
### 2. Clone JSON repository to local machine
   
    git clone https://......

### 3. Inside local JSON create file `new.json`
    cd JSON 
    touch new.json
or    

    cat > new.json
    "control + c"

### 4. Add file under git
    git add new.json

### 5. Commit a file
    git commit -m "newJSONFile"

### 6. Push file to external GitHub repository

    git push 

or u can add file via GitHub (click on button Add file)"

### 7. Edit the contents of the `new.json` file - write information about yourself (name, age, number of pets, future desired salary). Everything is written in JSON format

    cat >> new.json 
or

    vim new.json    
    add information in JSON format
result

    https://github.com/chelovechek159/JSON/blob/main/new.json
 
### 8. Push changes to an external repository
    git add new.json
    git commit -m "text"
    git push 

### 9. Create file `preferences.json`
 
    cat > preferences.json

### 10. Add information about your preferences (Favorite movie, favorite series, favorite food, favorite season, country you would like to visit) to the `preferences.json` file in JSON format

    cat >> preferences.json
    add information in JSON format
result

    https://github.com/chelovechek159/JSON/blob/main/preferences.json

### 11. Create a file `skills.json` add information about the skills that will be studied in the course in JSON format

    cat > skills.json
	add information in JSON format
result

    https://github.com/chelovechek159/JSON/blob/main/skills.json
### 12. Send 2 files at once to an external repository
    git add .
    git commit -m "text"
    git push

### 13. On the web interface, create a file `bug_report.json`
    Add file
    Create new file
### 14. Make Commit changes (save) changes on the web interface
    Add changes
    click on the button [Commit changes]
### 15. Modify the `bug_report.json` file on the web interface to add a bug report in JSON format
    edit file
    write bug report in JSON format
result

    https://github.com/chelovechek159/JSON/blob/main/bug_report.json
### 16. Make Commit changes (save) changes on the web interface
    click on the button [Commit changes]

### 17. Synchronize external and local JSON repository 
    git pull

