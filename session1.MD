**Session1:**

````
 git init
 git add <filename> --> *staging/temp area*
 git add <file1> <file2> --> *Adding multiple files*
 git add . --> *add all files at once*
 git commit -m "some-message"
 .gitignore --> *can add files to ignore certain type of files not required to commit search google for (sample .gitignore)*
 git config --global user.name "muralikrishnavujji" --> *These can be seen inside /home/user/.gitconfig*
 git config --global user.email "vujjimuralikrishna@gmail.com"
 .git-credentials --> *stores the token value created to push files to remote origin*
 git log --> u can check who committed the file mainly the users
 Now create an account in github and create a repo with same name that u created in ur local to be in sync.
 git remote add origin <url of github repo u just created> --> *https://github.com/my-daws78s/git-commands.git*
 git push -u origin master --> this was throwing error in class as Siva used a different laptop of his friend and trying to push..
 ````
 * Control Panel --> User Accounts --> Credential Manager --> Windows Credentials --> Generic Credentials --> and remove the github keys
 
 **Summary:**
 * I am developer1, today I created a repo in my local and pushed to github.
 * Tomorrow dev2 will come and pull that repo in his local from remote central repo..

 * Issues: I did not find the approach of adding remote origin working here, instead I cloned the rep in my local and just used the push command.
 * MuraVuj@LT-AAD-WhtDXQ1z MINGW64 /c/Sirius/DevopswithSiva_31Mar2024_daws-78s/repos/git-commands (main)
 * $ git add . ; git commit -m "reference for session1 git commands.." ; git push -u origin main

