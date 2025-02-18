# Task 4 & 5 - Branch Creation, Merging, and Documentation

## Task 4 - Create a `Temp` Branch and Add `Task_3.md`
1. `git checkout -b Temp` *(Create and switch to a new branch)*
2. `echo # Task 3 > Task_3.md` *(Create `Task_3.md` file)*
3. `git add Task_3.md` *(Stage the file)*
4. `git commit -m "Add Task_3.md file in Temp branch"` *(Commit the file)*
5. `git push -u origin Temp` *(Push the Temp branch to GitHub)*

## Task 5 - Merge `Temp` Branch into `master`
1. `git checkout master` *(Switch back to `main` branch)*
2. `git merge Temp` *(Merge `Temp` branch into `main`)*
3. `git push origin master` *(Push the merged changes to GitHub)*
4. `git branch -d Temp` *(Delete the `Temp` branch locally)*
5. `git push origin --delete Temp` *(Delete the `Temp` branch from GitHub)*