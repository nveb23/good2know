# Git
* unstage a file  
    * `git reset HEAD -- path/to/file`  // old
    * `git restore --staged <individual_file>` // preferred
* unstage everything  
    * `git reset HEAD -- `
    * `git restore --staged .`
