# Commands used for the rebase-test

1. **git rebase -i HEAD~9**

2. **change the file to this configuration:**

    * edit 0fc7ffe Add some weird ideas
    * squash 51788cc Changed my mind about that idea
    * squash d031bd3 Additional idea, possibly adding a typo
    * squash add8084 fix typo
    * edit 3282330 Add feature 1
    * squash 353ceda Additional note to feature 1
    * edit e402aae Add feature 2
    * edit 5ddb426 Additional note about feature 2
    * pick 91f7590 Final sentence about this exercise and expectation

3. **git commit --amend** to change the name of the commit

4. **git rebase --continue**



