# Tutorial

How to do the simple stuff
Once it is set up:
- git add -all
  If you make a mistake and want to cancel this: 
  - for a single file git reset filename.txt  
  - To undo git add . use *git reset*
- git commit -m "COMMIT MESSAGE" --all
- git push -u origin master
Here *master* is the local dir and *origin* is the web address

If the wrong remote is set
- git remote rm origin
- git remote add orign "URL"

Question:
- is there a difference between git add .  and git add -all ?
- How to see what is currently changed: is it easy to compare 2 files?
- work more with master/head etc
