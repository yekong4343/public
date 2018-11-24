 create a new repository on the command line
 echo "# public" >> README.md
git init
git add README.md
git commit -m "first commit"
git remote rename origin origin-old
git remote add origin https://github.com/yekong4343/public.git
git push -u origin master
