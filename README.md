################
This is a sample repo, hello
md = markdown file

Git Bash command

# copy repo to local
clone https://github.com/Vic2Skants/Example-repo.git example_repo

#liste file
ls -la 

#clear editor
cltr l 

#get status 
git status

____________
#Checkout det som er ikke submit
git checkout.README.md

#Check out den versjon som er sjekket in
git checkout master
#or versjon , ta med dele string av log
git checkout a418389abcafdc1aec22e7 
______________

# add single file or add changes to a file
git add README.md

#See changes to file 
git diff README.md

#Submit to changes 
git commit -m "initial commit"

#Send/Push files to github
git push -u origin main
(origin -which branch )
(master - Code frontpage of github)


#for å sjekke log
git log
_____________________________



#…or create a new repository on the command line
echo "# Example-repo" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/Vic2Skants/Example-repo.git
git push -u origin main


#…or push an existing repository from the command line
git remote add origin https://github.com/Vic2Skants/Example-repo.git
git branch -M main
git push -u origin main


