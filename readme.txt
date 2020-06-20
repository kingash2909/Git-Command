
Git  commands 
---------------------------------------------------------------------------------------------------------------------
#initilaze git
git init


#add project
git add .


git commit -m "select_the_proj_dir"
eg: git commit -m "melan"

#...Create repositry and and add the link of same
git remote add origin https://github.com/kingash2909/repo-name.git
eg: git remote add origin https://github.com/kingash2909/temptestt.git



#...after this u may ask user id and pass of github entr and proceed

#...now push the data to the master of repo created.
git push -u origin master
or(if abv didnt wrks the use below1)
git push -f origin master


done.....

---------------------------------------------------------------------------------------------------------------------

#...To remove the file and folder from repo

#this will remv the file
git rm -r folder_or_filename

# to delete u need to use this command after abv 1..
git commit -m "removing files"

#and then commit the changes and push.....
git push



done......



