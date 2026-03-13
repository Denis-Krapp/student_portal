## 1. What does HEAD represent?
HEAD represent your current position in repository's commit history. It points which commit version and branch you're using now.

## 2. Under what conditions does a merge conflict occur?
When we merge branches with different content: in one branche file was deleted while in other it was edited; one or several lines were edited, but differently; large sections of code were edited completely differently. The same conflicts may appear when we pull changes to local branch.

## 3. What is the difference between git clone and git pull?
We use ```git clone``` when we want to get a project for the first time. We use ```git pull``` when we already have project, it gives us the opportunity to update our local version of project with remote changes.
