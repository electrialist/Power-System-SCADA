Power-System-SCADA
==================

A design and implementation of a miniaturized Power System SCADA integrated in a web-mobile application.


###Repo Merging/Pulling Rules


1. Before doing any work. Make sure you pull the latest version of `master` branch.
2. Create your own `branch`.
3. Make your modifications in your own `branch`.
4. Make sure that your work is not too behind in the `master` branch! Otherwise, you will have problems in merging your work.
5. Before merging to 'master' make sure you pull once again the lasest version of `master`.
6. Checkout to 'master' then merge your `branch` to `master`.
7. Make sure to check if the `master` branch works before you push your code to `origin`. We'll define testing methods later for everyone to do before pushing to origin. The point is not to break the master line of code.
8. If you break `master`, make sure to FIX it before Push.
9. Push all branches to `origin`.

###Basic git routine
```
1. git clone "Repo URL" folderName 
---Perform this command when you dont have the current repository you wish to contribute.
2. git pull
---Pull the current master branch in the repository.
3. git checkout -b branchName
---checkout the master branch then switches to your newly created branch "branchName".
4. git add .
--- add some files you add in the current folder/repository
5. git commit -a -m "Your commit description here"
---commit your work in the current branch
6. git checkout master
---Switch to master branch
7. git merge branchName
---Merging your recent work to master branch
8. git push origin
---Push your work to the master branch
```
