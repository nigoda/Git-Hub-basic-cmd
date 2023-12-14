CREAE A NEW REPOSITORY ON THE COMMAND LINE

echo "# DESCRIPTION" >> README.MD

git init

git add . # or git add {filename}

git commit -m "comment"

git branch -M main

git remote add origin https://github.com/nigoda/repo-name.git

git push -u origin main

--------------------------------------------------
PUSH AN EXISTIING REPOSITORY FROM THE COMMAND LINE

git remote add origin https://github.com/nigoda/repo-name.git

git branch -M main

git push -u origin main

--------------------------------------------------




