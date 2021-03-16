# Walmart Challenge

This project uses [Git Submodules](https://git-scm.com/book/en/v2/Git-Tools-Submodules).

If you're cloning this repo, you must execute the following commands:

    git submodule init
    git submodule update


This repo purpose it's to join the `front end`, `back end` and `mongo database` into a single `docker-compose`.

You can start this project by running:

    docker-compose build
    docker-compose up

or just `dcb && dcup`, if you have zsh extensions to docker-compose.

Take a look into the children repositories:

- [Front end](https://github.com/paulomontoya/walmart-challenge-front)

- [Back end](https://github.com/paulomontoya/walmart-challenge-back)