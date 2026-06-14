1\. What is git and why it is used in Devops?

*    It is a distributed version control system where we can track the changes in the source code, and allows multiple developers to  collaborate efficiently.
*    It allows versioning, merging, branching and maintaining complete history of the project.
*    In devops it is the reliable foundation for the CI/CD, automated deployments \& helps in collaborative workflows.



2\. How does Git differ from centralized version control systems?

* Unlike centralized systems (e.g., SVN), Git allows every developer to have a full local repository with complete history.
* This ensures offline work, faster operations, and better branching and merging capabilities.
* Centralized systems depend on a single server, creating a potential single point of failure.



3\. What are branches in Git, and why are they important?

* Branches are independent lines of development within a repository.
* They allow developers to work on features, bug fixes, or experiments without affecting the main codebase.
* Branching facilitates parallel development, reduces conflicts, and enables safe experimentation.



4\. Explain the difference between merging and rebasing.

* Merging combines changes of one branch into another while preserving commit history.
* Rebase is a Git operation that moves or reapplies your branch commits on top of another branch, creating a cleaner, linear history.
* Merging is safer for shared branches, while rebasing is used to maintain a clean history before integration.



5\. What is the difference between a commit, push, and pull?

* Records changes to the local repository.
* Sends committed changes to a remote repository.
* Retrieves and merge changes from a remote repository into the local repository.
* These operations ensure that code changes are synchronized across developers and environments.



6\.  What is the purpose of a remote repository?

* A remote repository is a central location where team members share code.
* It enables **collaboration**, **version tracking**, and integration with **CI/CD pipelines**.
* Platforms like GitHub, GitLab, and Bitbucket provide additional features such as **access control, issue tracking, and pull request management.**



7\. What are forks and clones, and how are they different?

* Clone: Creates a local copy of a remote repository into our local machines.
* Fork: Creates a personal copy of someone else’s repository, under the GitHub account
* Forks are used for **open-source collaboration**, while clones are used for **team development** within an organization.



8\. How do pull requests or merge requests work?

* Pull requests (GitHub) or merge requests (GitLab/Bitbucket) are a mechanism to **review and integrate code changes**.
* Developers submit their branch for review, where peers can **comment**, suggest **improvements**, or **approve changes**.
* Once approved, the changes are merged into the main branch, **maintaining code quality** and **collaboration standards**.



9\. How do access control and permissions work in remote repositories

* Repository owners can assign roles such as Admin, Developer, or Reporter to control read/write access.
* **Fine-grained permissions** ensure that only authorized users can merge, modify, or delete code, maintaining security and compliance.



10\. How do teams manage conflicts during merging?

* Conflicts occur when multiple developers modify the same lines of code.
* Git highlights conflicts during merge or rebase.
* Developers manually review the conflicting changes and decide which code should be kept.
* Merge or rebase frequently to keep branches up to date with the main branch.
