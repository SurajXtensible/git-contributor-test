 git filter-repo rewrites commit history to permanently update author names and emails.
Example Approach
Modify commit metadata using a script
Force push updated history to remote repository
Implications
Changes commit hashes (history rewrite)
Requires  git filter-repo
All collaborators must re-sync (re-clone or reset)
Higher risk in shared environments


