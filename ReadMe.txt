# cd "C:\Users\fgy\AppData\Local\Temp\Git00\"
# "C:\Users\fgy\AppData\Local\Temp\Git00\ReadMe.txt"

…or create a new repository on the command line

echo "# Git00" >> ReadMe.md
git init
git add ReadMe.md
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
git add ReadMe.txt
echo %date% %time% >> ReadMe.txt
git commit -m "Commit %date% %time%" -o ReadMe.txt

git push

rem !!!
git checkout ReadMe.txt



#### #####


mer. 24/01/2018 15:48:39,33 
jeu. 25/01/2018  8:48:37,30 
jeu. 25/01/2018  8:49:24,65 
jeu. 25/01/2018  9:01:18,69 
jeu. 25/01/2018  9:06:27,98
jeu. 25/01/2018 11:38:09,92 
jeu. 25/01/2018 11:37:20,99 
