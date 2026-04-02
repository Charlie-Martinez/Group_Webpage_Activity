## Branch Management Advice
### Each member should work within their own branch. Existing branches are as follows:
- main
  - Do not use this branch for making changes
- Charlie
- Ethan
- Johnny
- Jonathan


### After successfully cloning the repo, follow this guide to make your changes:
1. Switch to your branch: 
   - git checkout YourName
2. Pull up a list of the branches and confirm you see your name in green indicating you have successfully switched to your branch:
   - git branch -a
3. Make your code changes
4. Add & commit changes as normal:
   - git add index.html
   - git commit -m "Conventional commit message here"
5. Push changes:
   - git push origin YourName
6. Go to GitHub website and approve your pull request to merge your changes to repo
7. Use following commands to update your local files with new changes from repo:
   - git checkout main
   - git pull origin main
8. ** IMPORTANT ** Make sure to switch back to your branch with the following command and then repeat this guide to continue working
   - git checkout YourName