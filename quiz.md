Version Control with Git
========================

by Atlassian

# Module 1 Assessment
1. Which one of these statements about Git is true?

        A. Git helps manage the history of the project.
        B. Each version of the project is called a branch.
        C. A commit containing one small change to a project is not practical.

        Ans: A
        This is covered in 'DevOps and Git in a Nutshell'.


2. Which one of these statements about branches is true?

        A. The default branch is named "master".
        B. A branch contains a small part of the project.
        C. By default, a commit does not belong to a branch.

        Ans: A
        This is covered in 'DevOps and Git in a Nutshell'.


3. What is a request to merge your branch into another branch called?

        A. Code review
        B. Automated test
        C. Pull request

        Ans: C
        This is covered in 'DevOps and Git in a Nutshell'.


4. If a remote repository is offline, which one of the following is true?

        A. You must wait for the remote repository to become available.
        B. You can continue to work with the local repository.
        C. You can continue to work, but only with the current version of the project.

        Ans: B
        This is covered in 'DevOps and Git in a Nutshell'.


5. Which one of the following is true?

        A. Git does not scale to large projects.
        B. Git is owned by a single company.
        C. Git implements distributed version control.

        Ans: C
        This is covered in 'Git Overview'.


6. Which one of these statements about commits is true?

        A. A commit contains only the changes to the project since the previous commit.
        B. A commit is a snapshot of the project.
        C. Only the most recent commit is saved in the repository.

        Ans: B
        This is covered in 'Git Overview'.


7. Which location contains the list of files that will be included in the next commit?

        A. Working tree
        B. Remote repository
        C. Branch
        D. Staging area

        Ans: D
        This is covered in 'Git Locations'.


8. Which location contains the commit history of a project?

        A. Staging area
        B. Remote repository
        C. Branch
        D. Working tree

        Ans: B
        This is covered in 'Git Locations'.


9. When a file is first placed in the working tree, what is its status?

        A. Staged
        B. Modified
        C. Untracked
        D. Committed

        Ans: C
        This is covered in 'Commit to a Local Repository'.


10. What must you do to add a new file to the next commit?

        A. Push the file.
        B. Add the file to the staging area.
        C. Tag the file.
        D. Check out the file.

        Ans: B
        This is covered in 'Commit to a Local Repository'.


11. If you create a local repository in a folder with existing files, what will be the status of the files?

        A. Staged
        B. Untracked
        C. Committed
        D. Modified

        Ans: B
        This is covered in 'Commit to a Local Repository'.


12. Immediately after you commit, where is the commit located?

        A. Neither repository
        B. Remote repository
        C. Local repository
        D. Local repository and remote repository

        Ans: C
        This is covered in 'Commit to a Local Repository'.

13. Which one of these statements about remote repositories is true?

        A. A remote repository usually has a working tree.
        B. A remote repository usually has a staging area.
        C. By convention, remote repository names end in ".git".
        D. You must have one remote repository for each local repository.

        Ans: C
        This is covered in 'Create a Remote Repository'.

14. What is a local copy of a remote repository called?

        A. Branch
        B. Origin
        C. Clone
        D. Master

        Ans: C
        This is covered in 'Push to a Remote Repository'.

15. After you clone a repository, which one of the following is true?

        A. New commits to the local repository will automatically be pushed to the remote repository.
        B. The remote repository information is available in the local repository.
        C. New commits on the remote repository will automatically be added to the local repository.
        D. Only the most recent commit is available locally.

        Ans: B
        This is covered in 'Push to a Remote Repository'.

16. What is origin?

        A. The default branch name.
        B. The first version of a file in the repository.
        C. An alias for the remote repository's URL.
        D. The first commit of the repository.

        Ans: C
        This is covered in 'Push to a Remote Repository'.


17. What must you do to add a local commit to the remote repository?

        A. Push
        B. Stage
        C. Pull
        D. Merge

        Ans: A
        This is covered in 'Push to a Remote Repository'.


# Module 2 Assessment
1. In Git, what is modeled as a directed acyclic graph?

        A. The staging area.
        B. The working tree.
        C. The commit history.

        Ans: C
        This is covered in 'Git's Graph Model'.


2. How are Git commits connected?

        A. A commit object contains the SHA-1 of its child or children.
        B. A commit references its parent(s).
        C. The staging area lists the connections.

        Ans: B
        This is covered in 'Git's Graph Model'.

3. What is a Git ID?

        A. The name of a Git object.
        B. The ID of the local repository.
        C. The user's name and email address.

        Ans: A
        This is covered in 'Git IDs'.


4. If a large file changes by one character, what would you expect to happen to its corresponding SHA-1 value?

        A. It would slightly change.
        B. It would not change.
        C. It would change drastically.

        Ans: C
        This is covered in 'Git IDs'.


5. What do branch labels point to?

        A. The most recent commit of a branch.
        B. The initial commit of a branch.
        C. Every commit of a branch.

        Ans: A
        This is covered in 'References'.


6. How many HEAD references are in a local repository?

        A. One for each branch label.
        B. One for each commit.
        C. One.

        Ans: C
        This is covered in 'References'.


7. Which one of these statements is correct?

        A. A tag always points to a specific commit.
        B. A tag is another name for a branch label.
        C. The HEAD reference always points to a tag.

        Ans: A
        This is covered in 'References'.


8. What happens when a branch is created?

        A. The HEAD reference changes.
        B. A branch label is created.
        C. Commits are copied.

        Ans: B
        This is covered in 'Branches'.


9. Which one of these statements is correct?

        A. Checkout updates the working tree and HEAD reference.
        B. Checkout prevents others from changing a branch.
        C. Checkout retrieves content from the remote repository.

        Ans: A
        This is covered in 'Branches'.


10. What does a detached HEAD mean?

        A. The HEAD reference does not point to anything.
        B. The HEAD reference points to a branch label.
        C. The HEAD reference points directly to a commit SHA-1.

        Ans: C
        This is covered in 'Branches'.


11. What does "deleting a branch" immediately do?

        A. Deletes all of the commits of the branch.
        B. Deletes a branch label.
        C. Deletes only the commits that are unique to the branch.

        Ans: B
        This is covered in 'Branches'.


12. Which one of the following statements is true?

        A. A commit can only belong to one branch at a time.
        B. A merge always creates a new commit.
        C. Merging combines the work of branches.

        ANs: C
        This is covered in 'Merging'.


13. Which one of the following statements about fast-forward merges is true?

        A. The merge moves a branch label.
        B. The merge may change some commits.
        C. The merge may result in a merge conflict.

        Ans: A
        This is covered in 'Merging'.

14. If Git informs you that a fast-forward merge is not possible, which one of these statements is probably true?

        A. The merge has merge conflicts.
        B. The checked out commit has multiple parents.
        C. A commit was made on the base branch after the topic branch was created.

        Ans: C
        This is covered in 'Merging'.


15. Which one of these statements is true?

        A. The files in the working tree change after a fast-forward merge.
        B. A fast-forward merge results in a non-linear commit history.
        C. To perform a fast-forward merge, checkout the topic branch.

        Ans: A
        This is covered in 'Merging'.


16. Which one of these statements about a merge involving a merge commit is true?

        A. A merge commit results in a linear commit history.
        B. The merge is aborted if there are merge conflicts.
        C. Git places the result of the merge into a new commit.

        Ans: C
        This is covered in 'Merging'.


# Module 3 Assessment
1. Which one of the following statements about merge conflicts is true?

        A. Merge conflicts can not occur in Git.
        B. Merge conflicts can be fast-forward merged.
        C. Merge conflicts occur when a person needs to make a decision.

        Ans: C


2. Assume that you have a topic branch merging into a base branch. Which one of the following is involved in resolving a merge conflict?

        A. Checking out the topic branch.
        B. Pushing to the remote repository.
        C. Adding file(s) to the staging area.

        Ans: C


3. Assume that you have a topic branch merging into a base branch. Which one of these situations is most likely to create a merge conflict?

        A. Both branches update the header in README.md.
        B. The topic branch modifies fileA.txt. The base branch modifies README.md.
        C. In README.md, the topic branch modifies the header and the base branch modifies the footer.

        Ans: A


4. Which one of the following statements is true?

        A. A tracking branch label sometimes points to the same SHA-1 as the remote branch label.
        B. A tracking branch label always points to the same SHA-1 as the remote branch label.
        C. A tracking branch label never points to the same SHA-1 as the remote branch label.

        Ans: B(x) A


5. Which one of the following is most likely to have tracking branches?

        A. The staging area.
        B. A remote repository.
        C. A local repository.

        Ans: C


6. Immediately after you clone a repository, which one of these statements is most likely to be true?

        A. The local branch tip will be ahead of the tracking branch tip.
        B. There are no tracking branches.
        C. The tracking branch label and local branch label point to the same commit.

        Ans: C


7. If you perform a fetch and new objects are retrieved, which one of these is most likely to be true?

        A. The local branch and tracking branch will contain the exact same commits.
        B. The local branch label and tracking branch label will point to the same commit.
        C. The tracking branch label will point to a new commit.

        Ans: C


8. Which one of these statements is true?

        A. Pull does not update the local branch tip.
        B. Fetch does not update the local branch tip.
        C. Fetch may result in a merge conflict.

        Ans: B


9. Which one of these statements is true?

        A. Pull combines fetch and merge.
        B. Pull combines fetch and push.
        C. Push combines fetch and merge.

        Ans: A


10. A pull may result in which one of the following?

        A. A new checked out branch.
        B. A merge commit on the remote repository.
        C. A fast-forward merge.

        Ans: C


11. When should you avoid rebasing a branch?

        A. Always.
        B. If you have shared the branch.
        C. If a merge conflict occurs.

        Ans: B


12. Which one of the following statements is true?

A. A rebase never results in a merge conflict.
B. A rebase always results in a merge conflict.
C. A rebase may result in a merge conflict.

Ans: C

13. Which one of the following statements is true?

        A. A rebase never rewrites the commit history.
        B. A rebase may rewrite the commit history.
        C. A rebase always rewrites the commit history.

        Ans: C

14. Which one of the following statements is true?

        A. A rebase always creates a merge commit.
        B. A rebase may result in a merge conflict.
        C. Rebasing a topic branch involves checking out the base branch.

        Ans: B

15. Which one of the following statements is true?

        A. An interactive rebase never removes existing commits.
        B. An interactive rebase may involve a single branch.
        C. An interactive rebase must involve two or more branches.

        Ans: B


# Module 4 Assessment
1. Which one of these is the main goal of a pull request?

        A. Obtain a clone of a repository.
        B. Create a branch.
        C. Merge a branch into a project.

        Ans: C


2. Which one of these statements is true?

        A. A pull request can act as a form of review and approval.
        B. A pull request can be made only when a branch is being merged.
        C. A pull request must be made from a forked repository.

        Ans: A


3. Which one of these statements is true?

        A. A pull request merge can not be fast-forwarded.
        B. Merging a pull request may result in a merge conflict.
        C. Merging a pull request always creates a merge commit.

        Ans: B


4. Which one of these statements is true?

        A. A pull request must include a forked repository.
        B. Pull requests can not be modified.
        C. Pull requests can facilitate team discussion.

        Ans: C


5. When can you open a pull request?

        A. When you want feedback on your work.
        B. Only when the branch is created.
        C. Only when the branch is ready to be merged.

        Ans: A


6. Which one of these is true about squash merges?

        A. A squash merge can result in deleted commits.
        B. A squash merge can not be done when merging a pull request.
        C. A squash merge creates a merge commit.

        Ans: A


7. Which one of these statements is true?

        A. A fork is considered the source of truth.
        B. A fork is a remote repository.
        C. A fork is an upstream repository.

        Ans: B


8. Which one of statements about forks is true?

        A. The upstream respository never has access to the fork.
        B. The upstream repository always has access to the fork.
        C. The upstream repository may have access to the fork.

        Ans: C


9. After forking a repository, which one of these statements is true?

        A. The two repositories can not be synchronized.
        B. The two repositories will automatically remain synchronized.
        C. The commit histories of the two repositories may begin to differ.

        Ans: C

10. Which one of these statements is true?

        A. Cloning a forked repository creates a local repository.
        B. There is no reason to clone a forked repository.
        C. A fork and a clone are the same thing.

        Ans: A


11. Assume that you have a forked repository and an upstream repository. Who selects the merge strategy if a pull request is merged?

        A. The creator of the topic branch.
        B. The person merging the pull request.
        C. The requester.

        Ans: B

12. Which one of these statements about centralized workflows is true?

        A. There is usually a single branch on the remote repository.
        B. Pull requests are common in centralized workflows.
        C. Using a centralized workflow is discouraged.

        Ans: A

13. Which one of these statements about feature branch workflows is true?

        A. Using a feature branch workflow is discouraged.
        B. Pull requests are not possible in feature branch workflows.
        C. Most work is done on a feature branch.

        Ans: C

14. Which one of these statements about forking workflows is true?

        A. Using a forking workflow is discouraged.
        B. The forked repository must have write access to the upstream repository.
        C. A forking workflow involves multiple remote repositories.

        Ans: C

15. Which one of these statements about Gitflow workflows is true?

        A. Gitflow workflows can accomodate hotfixes.
        B. Gitflow workflows contain no long-running branches.
        C. Gitflow workflows work best with small projects.

        Ans: A





