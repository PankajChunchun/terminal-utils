# git

1. Discard all unstaged files from git
    ```bash
    git clean -df
    git checkout -- .

    ```
1. Log all the commits
    ```bash
    git log --pretty=format:"%h %s" --graph

    ```

1. Git status
    ```bash
    git status

    ```

1. Add all changed files to staging area
    ```bash
    git add .

    ```

1. Commit 
    ```bash
    git commit -m "commit msg here"

    ```

1. List all remotes
    ```bash
    git remote -v

    ```

1. List all existing branches
    ```bash
    git branch -av

    ```

1. Add remote repo to a git
    ```bash
    git remote add <shortname_of_remote> <remote_url>

    ```

1. Git Push
    ```bash
    git push <shortname_of_remote> <branch>

    ```

1. Git Pull
    ```bash
    git pull <shortname_of_remote> <branch>

    ```

1. Delete a local branch
    ```bash
    git branch -d the_local_branch

    ```

1. Delete a remote branch
    ```bash
    git push origin :the_remote_branch

    ```

1. Duplicate a branch
    ```bash
    git checkout -b new_branch old_branch

    ```

1. Associate Atom Text Editor with your git
    ```bash
    git config --global core.editor "atom --wait"

    ```

1. GUI Git Tool
    ```bash
    gitk --all &

    ```

1. Rewriting History
    ```bash
    git rebase -i <branch/commit_id>

    ```

1. Reset merge changes
    ```bash
    git reset --merge ORIG_HEAD

  	```
	
1. Stop tracking a file [[More Info](http://stackoverflow.com/a/3320183/2745762)]
    ```bash
    git update-index --assume-unchanged [<file> ...]

  	``` 
	
1. Start tracking a file [[More Info](http://stackoverflow.com/a/3320183/2745762)]
    ```bash
   git update-index --no-assume-unchanged [<file> ...]

  	```


License
=======

    Copyright 2016 Nishant Srivastava

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

       http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.

