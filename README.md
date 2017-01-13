# phase-0-gps-1
  501  ls
  502  cd gps
  503  git clone https://github.com/joshmun/phase-0-gps-1.git
  	-we were syncing our local drive with the repository on GitHub; indicating which project we're working on
  504  ls
  505  git status
  	-checking for correct cloning/repo
  506  cd phase-0-gps-1/
  507  git status
  	-which branch we're on, and any changes that have occurred "what's going on"
  508  git branch
  	-lists the branches
  509  touch awesome_page.md
  510  git add awesome_page.md
  	-staging this file specifically to be saved/committed
  511  git status
  512  git commit -m "initial commit"
  	-creates a save point/commits
  513  git status
  514  git push origin
  	-syncing what's local with GitHub repository
  515  git co -b add-command-log
  	-created a new branch and switched to it
  516  ls
  517  subl README.md
  518  history