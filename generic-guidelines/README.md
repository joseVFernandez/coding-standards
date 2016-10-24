Generic Coding Guidelines
=========================

Code
----

1. Passes all the tests
2. Contains no duplication
3. Clearly expresses the programmer’s intent
4. Follows the platform standard style guide
5. Minimizes code, although readability is always preferred over brevity
6. It's well documented

Commits
-------

1. Are done early and often
2. Are atomic, clear and concise
3. Only contain related changes
4. Have insightful and descriptive commit messages
5. Copying and moving a file happens in a different commit from any changes done to it

Branches
--------

1. Follow the git flow convention (http://nvie.com/posts/a-successful-git-branching-model/)
2. Are continuously up to date with its parent branch
3. Are only merged into the main branches (develop, master, staging) by pull requests

Pushes
------

1. Are not done directly to the main branches (develop, master, staging)
2. Do not contain any commented code
3. Are linted
4. Do not have any warnings
5. Do not change published history

Pull Requests
-------------

1. Have the necessary unit tests
2. Before being opened, the code was reviewed with a git diff against the target branch
3. Have assigned reviewers
4. Close the source branch
5. Have clean diffs against the target branch

Repository
----------

0. Has a Readme.md file which establishes the dependencies and  the steps to get the project running from zero
1. Contains all the necessary files to get the project up the ground
2. Does not contain any auto generated files
3. Does not contain developer related configuration files
4. Uses .editorconfig to mantain same coding standards and avoid whitespace diffs
