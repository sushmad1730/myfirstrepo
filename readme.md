This is a sample for creating repo

this is for second commit on vs code

this is the change done directly on git, to update this in vs code we need to pull the code from this repo
-- used git pull origin branch_name to pull the data from repo 
-- git push origin branch_name to push the data 
-- git status :  it shows the status, modified or no change, upto date 
-- stage the changes : git add . (add all files)
 -- particular file : git add filename.extension
 --commit : git commit -m "Your message describing the change"
 -- git push origin main


 I AM WORKING IN NEW BRANCH NOW. 

 STEPS TO CREATE NEW BRANCH ON VSCODE

 1. CHECK BRANCH - git branch 
 2. CREATE BRANCH - git branch firstbranch 
 3. SWITCH TO NEW BRANCH - git checkout firstbranch (or) git switch firstbranch

 * TO CREATE AND SWITCH AT SAME TIME : git checkout -b firstbranch 

 4. PUSH BRANCH TO GITHUB: git push -u origin firstbranch

 I MADE A CHANGE IN THE FILE ON GIT HUB DIRECTLY

 I HAVE ADDED LINES IN MAIN DIRECTLY ON GIT HUB AND DID NOT DO A PULL HERE AND TRYING TO RAISE PR


TRYING TO RAISE PR AGAIN FROM firstbranch after doing pull on both main and firstbranch 

below is the reason it did not worked before 

-- when we try that the first branch will be few commits the main so we cannot raise pr 
-- It asks us to raise pr from main to firstbranch first 
--when we try to do that there will be conflits
-- resolve conflicts on git, and accept pr
--now git is not updated on vs code. to update it do a git pull on firstbranch
-- if you raise a pr from firstbranch to main, do git pull on the main branmch too 

DOING A CHANGE IN FIRSTBRANCH AND TRYING TO CHECK IF IT DIRECTLY UPDATED ON MAIN IF WE PUSH TO MAIN - WE CANNOT