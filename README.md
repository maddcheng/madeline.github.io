## To get to path:
1. Open terminal
2. `cd /Users/madd.cheng/Desktop/madelines_experiment`

## To open ATOM with project, inside project run:
1. `atom .`

## To initiate git repo in your project (this sets up project as github configurable), run. This only needs to happen once DONE!:
1. `git init`
2. Add git repo within directory. You will have to create an empty repo (destination address) on github:
`git remote add origin https://github.com/maddcheng/madeline.github.io.git`

## After Making a Change in your Code:
1. Run `git diff` to show changes
2. If satisfied run, `git add .` to add changes to staging
3. Next run, `git commit -m 'some message here....'`
4. Finally, to push up to github run `git push origin master`
