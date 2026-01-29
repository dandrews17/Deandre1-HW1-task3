looking at these files it seems each branch implements a different aspect/ feature of this game

dev- development branch to merge branches
feature 1- made better guesses and added quit ability
feature 2-added logic for max guess attempts
feature 3- added expanded hint system
hot fix- made it so that 100 is included in the number generator

• Differences between merge, rebase, squash, and cherry-pick

I learned hands on that merges are more for catching branches up to each other
squash and rebase set the history up to be cleaner and in order repectively
cherry pick is actually goated for bringing in single commits into a branch even if the commit was from a different branch


• What you observed in the git history for feature1 vs feature2 vs feature3
feature2 had a different history because if the rebase, it more in order compared to the other ones because its history had that . The original history for feature3 was really all over the place, it highlighted the importance of being clear. If I came back to a project after even a week or two I could see those “got it done” types of comments being useless if I ever had to abort. Feature 1 overall had good history already and kept its original forked style history

• When you would use each strategy in real projects

I would use rebase on my own branch to create a fast forward merge when I merge on to the main branch. I would use cherry pick when I panic and make a new branch to fix a bug ASAP and then bring it in once it works. I would use squash after I rebase and am about to merge so that my comment history is easier to read with a single explanation of the feature that was added. Merging is just merging and I am sure I will be using that in every project I do 