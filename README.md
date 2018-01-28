# Branching tutorial

## Get your own copy of the repository
1. In GitHub, fork [nrsiward/branching_tut](https://github.com/nrsiward/branching_tut) to your account
2. Clone `branching_tut` from your account to your local disk

## Implementing a new feature
3. Create branch `feature1` (to implement a new feature)
4. Change line 2 in file1.txt

## Making an urgent bug fix at an inconvenient time
5. Stash
6. Change back to branch `master` (to make a bug fix before the feature is done)
7. Edit line 3 and line 4 in file1.txt
8. Stage and commit

## Finishing the new feature
9. Change to branch `feature1`
10. Pop the stash
11. Change line 4 in file1.txt (to finish implementing the feature)
12. Stage & commit

## Merge the new feature
13. Change to branch `master`
14. Merge branch `feature1`
15. Resolve conflicts

## Share with others
16. Push

## Clean up the uneeded branch
17. Delete local branch `feature1`
18. Push the branch deletion
