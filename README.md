# Project submission

part 2.b
  git add .
  git commit -m 'First commit'

part 3.b
  git commit -am 'Added task practice branching'

part 3.c
  git checkout -b feature/remove-tasks

part 3.d
  I remove the second task using vim, then:
    git commit -am 'Removed second task'

part 4.a
  git merge feature/add-tasks
  git merge feature/remove-tasks

part 4.b
  I encounter a conflict at file tasks.txt, I open a file with a text editor
  and pick the changes form the feature/add-tasks task, and then:
    git add tasks.txt
    git commit

part 5.a
  git checkout -b feature/update-tasks

part 5.b
  git commit -am 'Added Review task'

part 5.c
  git rebase

  no problem!

part 7.b
  git revert HEAD

part 7.c
  git reset --hard HEAD~2

part 8.b
  git push -u origin master
