# git

### Important Notes and commands related to GIT ###

# git : Is a local version control system

# github, bitbucket, gitlab are the Central Version Systems

## What is GIT ?
----------------
Git is a version control system used by almost all the organizations to version control their development and parallel development using branches.

## What is a branch in GIT ?
-------------------------
A branch is a copy of the code which allows the developers to test without touching the main code and this helps multiple developers to contribute parallely.

By default, main is the branch which should be the source of truth or production ready code.

## How can you control parallel development and how multiple developers can contribute and develop the code parallely ?
---------------------------
A branch is a version of your repository, or in other words, an independent line of development. A repository can contain multiple branches, which means there are multiple versions of the repository.

Among all, main / master branch is something which you should always a checkout to create a new /feature branch

## Git Branch Naming Strategy
----------------------------
Branching Naming Strategy will be based on the organizational standards.  

And based on what you're working on, name should define that.

Typically, either you work on  :
    a)  feature       [ feature/payment-enhancement ,  feature/password-auth ]
    b)  hotfix        [ hotfix/defect-correction ]
    c)  bug           [ bug/payments-correction ]
