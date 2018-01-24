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
echo %date% %time% >> readme.txt
git commit -m "Commit %date% %time%" -o Readme.txt
git push


#### #####


mer. 24/01/2018 11:01:25,24 
mer. 24/01/2018 11:49:37,08 
mer. 24/01/2018 11:51:31,05 
mer. 24/01/2018 11:53:16,61 
mer. 24/01/2018 11:54:18,36 
mer. 24/01/2018 11:56:37,59 
mer. 24/01/2018 11:58:23,80 
