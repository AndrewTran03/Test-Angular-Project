# How to Setup an Angular Repository on GitHub Pages on Windows with Git Bash

- ```git clone``` (repository)
- For Gig Bash Users on Windows: ```ng build --output-path docs --base-href='//(repo name)\'``` [(StackOverflow Error Solution Reference)](https://stackoverflow.com/questions/42292761/angular-cli-build-with-base-href-also-return-programs-folder-when-using-git-bash)
OR
- For All Other Terminal Users: ```ng build --output-path docs --base-href='/(repo name)/'```
- ```git add .```
- ```git commit -m "(message)"```
- ```git push origin (branch-name)```
- Go to ```"Settings > Pages"``` on GitHub and set the ```Branch``` to be the desired branch you want and the output directory to be ```docs```
- You have just successfully deployed your Angular Application successfully! Congratulations!