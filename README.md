# GITHUB - homework (JSON)
## 1. Create a remote repository called JSON
In the header on the main page on the right, click button `"+"` ->   
In the dropdown select `"New repository"` ->   
Enter "JSON" in the required `"Repository name"` field ->   
Click the `"Create repository"` button at the bottom of the page   
## 2. Clone the JSON repository to the local computer
vvsen@Vadim MINGW64 /c/vadim/qa/github   
`git clone https://github.com/VSenakosau/JSON.git`
## 3. Create a “new.json” file inside the local JSON
vvsen@Vadim MINGW64 /c/Vadim/QA/github/JSON (main)   
`touch new.json`
## 4. Add the file to Git
vvsen@Vadim MINGW64 /c/Vadim/QA/github/JSON (main)   
`git add new.json` or `git add .`
## 5. Commit the file
vvsen@Vadim MINGW64 /c/Vadim/QA/github/JSON (main)   
`git commit -m "Commit a file"`
## 6. Send the file to a remote GitHub repository
vvsen@Vadim MINGW64 /c/Vadim/QA/github/JSON (main)   
`git push`
```
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 12 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 281 bytes | 281.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
To https://github.com/VSenakosau/JSON.git
   9254277..307d8b8  main -> main
```
## 7. Edit the contents of the file “new.json” - write information about yourself (full name, age, number of pets, future desired salary). Write everything in JSON format.
We use nano editor to edit the file   
vvsen@Vadim MINGW64 /c/vadim/qa/github/JSON (main)   
```
$ nano new.json
{
"name": "Senakosau Vadzim",
"age": 36,
"pets": 1,
"future_salary": 4700
}
```
Ctrl+O enter   
Ctrl+X enter      
## 8. Send the changes to a remote repository
vvsen@Vadim MINGW64 /c/vadim/qa/github/JSON (main)   
`git add .`   
vvsen@Vadim MINGW64 /c/vadim/qa/github/JSON (main)   
`git commit -m "add information to new.json"`   
[main be28cd3] add information to new.json   
 1 file changed, 7 insertions(+)   
vvsen@Vadim MINGW64 /c/vadim/qa/github/JSON (main)   
`git push`   
Enumerating objects: 5, done.   
Counting objects: 100% (5/5), done.   
Delta compression using up to 12 threads   
Compressing objects: 100% (3/3), done.   
Writing objects: 100% (3/3), 360 bytes | 360.00 KiB/s, done.   
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0   
To https://github.com/VSenakosau/JSON.git   
   307d8b8..be28cd3  main -> main   
## 9. Create a preferences.json file  
vvsen@Vadim MINGW64 /c/vadim/qa/github/JSON (main)   
`touch preferences.json`
## 10. In the preferences.json file, add information about your preferences (favorite movie, favorite series, favorite food, favorite season, country you would like to visit) in JSON format
We use nano editor to edit the file    
vvsen@Vadim MINGW64 /c/vadim/qa/github/JSON (main)
```
nano preferences.json
{
"favorite_movie": "1+1",
"favorite_series": "Breaking Bad",
"favorite_food": "Shawarma",
"favorite_time": "Summer",
"country_to_visit": "USA"
}
```
Ctrl+O enter   
Ctrl+X enter   
## 11. Create a skills.json file, add information about skills that are going to be learned at the course in JSON format
```
cat > skills.json
{
"skills": [
"Basic theory",
"Client-server architecture",
"HTTP methods",
"JSON, XML",
"API testing via Postman",
"Charles and Fiddler",
"Dev Tools",
"VPN",
"Mobile testing",
"Feature of iOS, Android",
"Build iOS apps on XCode",
"Android Studio",
"ADB"
]
}
```
Ctrl+O enter   
Ctrl+X enter   
## 12. Send two files at once to the remote repository
vvsen@Vadim MINGW64 /c/vadim/qa/github/json (main)   
`git add preferences.json skills.json`   
`git commit -m "sending preferences.json and skills.json"`   
`git push`   
## 13. Create the bug_report.json file at the web interface


