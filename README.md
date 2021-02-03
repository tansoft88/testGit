
Basic Commands

$git init   //initialize local Git repository
$git add <file> //add file(s) to index
$git status //check status of working tree
$git commit //commit changes in index
$git push //push to remote repository
$git pull //pull latest from remote repository
$git clone //clone repository into a new directory
$git rm --cached <file>  //remove file from staged
$git add . //add all files to staged 
$touch <file>  // to create a file 
$git branch <branchName> // creates a new branch
$git checkout <branchName> //switches to branch specified
Some Notes
$git config --global core.editor vim // i fixed the emac erros i.e the editor in git commit
- remember when editing in emacs i.e editor when about to commit

press i // to be able to type
press esc // to get out of the emax
type :wq //to save and exit emac

how to skip editing thru the editor
$git add .  OR $git add <file>
$git commit -m 'Changed <file>'

if you want to ignore some files or folder put it in gitignore folder created by $touch .gitignore


