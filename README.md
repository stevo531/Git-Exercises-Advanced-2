# GIT EXERCISES 
# PART1
1  git --version
    2  git config --global user.name "Stevo's'
    3  git config --global user.name "Stevo"
    4  git config --global user.name "Stevo's'
    5  git config --global user.email "stevo"
    6  git --version
    7  git config --global user.name "Steven Cyubahiro"
    8  git config --global user.email steven.cyubahiro24snhu@keplercollege.ac.rw     
    9  git config --global core.editor "code --wait"
   10  git config --global -e
   11  git config --global core.crlf true
   12  git config --help
   13  git config --help
   14  git config -h
   15  mkdir Moon cd
   16  git innit
   17  git init7
   18  git init
   19  mkdir Moon
   20  cd Moon
   21  git init
   22  dir
   23  git clone
   24  git clone https://github.com/stevo531/Clone-exercise.git
   25  cd Clone-exercise/
   26  code .
   27  git init
   28  git clone https://github.com/HIRWA13/Git-exercise.git
   29  touch test{1..4}.md
   30  git add test1.md && git commit -m "chore: Create initial file"
   31  git add test2.md && git commit -m "chore: Create another file"
   32  git add test3.md && git commit -m "chore: Create third and fourth files"      
   33  git status
   34  git add test4.md
   35  git log
   36  git commit -m "added test4 file"
   37  git log
   38  git log --oneline
   39  git rebase -i HEAD~3
   40  git rebase -i HEAD~3
   41  git log --oneline
   42  git log --oneline
   43  git rebase --continue
   44  git rebase --edit-todo
   45  git log --oneline
   46  rm -rf *
   47  rm -rf .git
   48  git init
   49  git clone https://github.com/HIRWA13/Git-exercise.git
   50  touch test{1..4}.md
   51  git add test1.md && git commit -m "chore: Create initial file"
   52  git add test2.md && git commit -m "chore: Create another file"
   53  git add test3.md && git commit -m "chore: Create third and fourth files"      
   54  git status
   55  git add test4.md
   56  git commit -m "chore: Create fourth file"
   57  git log
   58  git log --oneline
   59  git rebase -i HEAD~4
   60  git rebase -i HEAD~3
   61  git rebase -i --root
   62  git commit --amend
   63  git rebase --continue
   64  git rebase -i --root
   65  git log --oneline
   66  git rebase -i HEAD~2
   67  git rebase -i HEAD~3
   68  git rebase -i --root
   69  git reset HEAD^
   70  git status
   71  git add test3.md
   72  git commit -m "Chore: create third file"
   73  git log
   74  git rebase -i --root
   75  git rebase --continue
   76  git rebase -i --root
   77   git add unwanted.txt
   79  git commit -m "unwanted commit"
   80  git rebase -i --root
    git rebase -i --root
   83  git rebase -i HEAD~1
   84  git rebase -i HEAD~2
   85  git log --oneline
   86  git rebase -i --root
   87  git log --oneline
   88  git checkout -b ft/branch
   89  git add test5.md
   90  git commit -m "Implemented test 5"
   91  git log --oneline
   92  git checkout master
   93  git cherry-pick f5f8999
   94  git log --graph
   95  git reflog
   # PART2
     git checkout -b ft/new-feature
   98  git add feature.txt
   99  git commit -m "Implemented core functionality for new feature"
  100  git checkout master
  101  git add readme.txt
  102  git commit -m "Updated project readme"