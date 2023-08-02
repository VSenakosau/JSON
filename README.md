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
