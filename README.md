titanRaspi
==========

My Raspberry Pi Project code will live here

#Create a subfolder called Hello-World in my git repo
$ mkdir ~/Hello-World

$cd ~Hello-World

#Initialize this folder with git files  on your local repo
$git init

#create the file
touch README

#Stage README (add it to the list of files to be committed)
$git add README

$git commit -m 'first commit andymenonseti'

# Now update all of this to remote git repository
# Create a *Remote* Push called *origin*
$git remote add origin https://github.com/andymenonseti/titanRaspi.git

# Finally, push the updates to the *master* branch
$ git push origin master
