# Blind Date

## Install it

In a Git repository, type:

    curl -O --silent http://github.com/entryway/blind-date/raw/master/pre-commit && mv pre-commit ./.git/hooks/pre-commit && chmod +x ./.git/hooks/pre-commit
    
## What is it

This pre-commit hook for git ensures that you're hitched to the right person to avoid a lot of git commit --amend after you forget who you're hitched to.

* requires git repository
* requires [hitch](http://github.com/therubymug/hitch) gem

## Installation, again

    cd your_project_directory
    wget http://github.com/entryway/blind-date/raw/master/pre-commit
    mv pre-commit .git/hooks/pre-commit
    chmod +x .git/hooks/pre-commit

Happy hitching