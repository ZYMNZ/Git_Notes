# GIT Commands

## Checking the Status

- `git status`
  - (when the file is colored `RED` then it means it's not in the staging area)
  - (when it's `GREEN` then it's in the staging area)

## Adding

### (to add it to the staging area)

- (Staging area: usefull to check the code before commiting it, and to tell git to track it )

- `git add file1`
- `git add file1 file2`
- `git add *.txt`
- `git add .` (this adds the entire directory recursively)

## Help

- `git config --help`
  (press 'space' to go the next page)
  (press 'q' to exit)

- `git config -h` (short summary of the command and it's options)

- `git ls-files` (to check the files in the staging area)

- `git commit -m "..."` (we commit with a short comment)
- `git commit -am "..."` (we commit all the changes)
- `git commit` (we commit with a long comment)

# ONE WAY OF REMOVING A FILE (3-ish steps)

- `rm file1.txt` (when we remove a file it gets removes from the folder BUT it's still in the 'Staging area' so we have to remove it from there too!)

- `git ls-files` (to see the files in the Staging Area)

- `git add file1.txt` (to remove the file from Staging area)[Yes it's seems like adding but this is the way to remove it]

# THE OTHER WAY (1 step)

- `git rm fil1.txt` [*.txt] (this will remove it in both the folder and the staging area)
