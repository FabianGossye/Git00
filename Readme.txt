# cd "C:\Users\fgy\AppData\Local\Temp\Git00\"
# "C:\Users\fgy\AppData\Local\Temp\Git00\Readme.txt"

…or create a new repository on the command line

echo "# Git00" >> README.md
git init
git add README.md
git commit -m "Commit 20180124093144 Clone "
git remote add origin https://github.com/FabianGossye/Git00.git
git push -u origin master

…or push an existing repository from the command line

git remote add origin https://github.com/FabianGossye/Git00.git
git push -u origin master

…or import code from another repository

# cd "C:\Users\fgy\AppData\Local\Temp\Git00\..\GitClone\."
git clone https://github.com/FabianGossye/Git00.git
# cd "C:\Users\fgy\AppData\Local\Temp\Git00\..\GitClone\Git00"

cd "C:\Users\fgy\AppData\Local\Temp\Git00\"
cd "C:\Users\fgy\AppData\Local\Temp\Git00\..\GitClone\Git00"
git pull
echo %date% %time% >> Readme.txt
git commit -m "Commit %date% %time%" -o Readme.txt
git push

rem !!!
git checkout Readme.txt



#### #####


mer. 24/01/2018 15:48:39,33 
