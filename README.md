# Git Flow

- § mkdir <folder_name>

- § cd <folder_name>

## initialiser git-flow

- § git flow init

- § touch README.md

- § git add -A

- §git commit -m "first commit"

- § git remote add origin git@github.com:Nicolas-Turck/git-flow.git

- § git push -u origin master

## nouvelle feature

- § git flow feature start <feature_name>

- § touch <file_name.extension>

- § git add -A

- § git commit -m "......."

## publication sur serveur distant

- § git flow feature publish <feature_name>

## feature terminer 

-§ git flow feature finish <feature_name>

## Release

- § git flow release start v0.1

on termine avec 

- § git flow release finish v0.1

## publication des modifications

- § git push origin --tags

## push sur la master 

- § git push origin master

## hotfix

# creation branch hotfix

- § git flow hotfix start bug

- git add ... git commit ...

# terminer avec 

- § git flow hotfix finish bug 


