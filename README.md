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
Ctrl+O enter (save)      
Ctrl+X enter (exit)        
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
Ctrl+O enter (save)      
Ctrl+X enter (exit)   
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
Ctrl+O enter (save)      
Ctrl+X enter (exit)     
## 12. Send two files at once to the remote repository
vvsen@Vadim MINGW64 /c/vadim/qa/github/json (main)   
`git add preferences.json skills.json`   
`git commit -m "sending preferences.json and skills.json"`   
`git push`   
## 13. Create the bug_report.json file at the web interface
We have to go to the GitHub page and create a file from there   
```
Click "Add file", select "Create new file" ->
-> Enter the file name "bug_report.json"
```
## 14. Make Commit changes (save) changes on the web interface
```
click the "Commit changes" button ->      
if necessary, enter information in the Commit message and Extendeddescription fields ->   
 click the "Commit changes" button   
```
## 15. On the web interface, modify bug_report.json file, add bug report in JSON format
```
Click on the file name ->
-> Click on the "Edit this file" icon ->
-> Enter data
```
enter the following information
```
{
  "id": 128,
  "severity": "trivial",
  "environment": "Windows 11 Pro , Chrome 112",
  "title": "The message in the tooltip begins with a lowercase letter when hovering over the image of the link [Argentine peso forecast: ARS seeking new bottom amid longstanding and persistent economic woes] on the https://capital.com/argentine-peso-forecast-ars page",
    "stepsToReproduce": [
    "1. Navigate to capita.com",
    "2. Scroll down to the [Financial News] block",
    "3. Click tab [Forex]",
    "4. Select section [USD latest: GBP/USD, EUR/USD, USD/JPY trading setups]",
    "5. Hover the cursor over the image of the links in the [USD latest: GBP/USD, EUR/USD, USD/JPY trading setups] section"
    ],
   "expectedResult": "The text of the tooltips on each image starts with a capital letter",
   "actualResult": "The text of the tooltips for the link image [Argentine peso forecast: ARS seeking new bottom amid longstanding and persistent economic woes] begins with a lowercase letter",
   "attachment": "(URL to the video)",
   "License": "All",
   "author": "SVadim"
}
```
## 16. Make Commit changes (save) changes on the web interface     
```
click the "Commit changes" button ->      
if necessary, enter information in the Commit message and Extendeddescription fields ->   
 click the "Commit changes" button   
```
## 17. Synchronize remote and local JSON repository.
vvsen@Vadim MINGW64 /c/vadim/qa/github/json (main)   
`git pull origin main`   
We have command successfully executed, with a notification that our new file bug_report.json has been added   
```
remote: Enumerating objects: 18, done.   
remote: Counting objects: 100% (18/18), done.   
remote: Compressing objects: 100% (15/15), done.   
remote: Total 16 (delta 8), reused 0 (delta 0), pack-reused 0   
Unpacking objects: 100% (16/16), 5.70 KiB | 104.00 KiB/s, done.   
From https://github.com/VSenakosau/JSON   
* branch            main       -> FETCH_HEAD   
7c36923..49d5f5f  main       -> origin/main   
Updating 7c36923..49d5f5f   
Fast-forward   
README.md | 111 ++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++   
1 file changed, 111 insertions(+)
```


