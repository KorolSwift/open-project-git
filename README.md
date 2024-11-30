# open-project-git
Команды для создания локального репозитория
cd projects
mkdir open-project-git   
ls
cd open-project-git  
git init
git status
touch guideline.txt 
touch README.md
git add --all    
git commit -m 'The first commit' 

echo 'Команды для создания репозитория можно найти в файле README.md' >> guideline.txt
git add --all 
git status
 
//Для клонирования c удаленного репозитория
cd projects
git clone git@github.com:KorolSwift/open-project-git.git 
cd open-project-git
echo 'Команды для создания локального репозитория' >> README.md
cat README.md
