Personnal cookiecutter
=======================

This is a personnal cookie cutter taht I use for data science projects.
It uses poetry to manage python packages and poe the poet to create quick commands.

Installation
------------

Create a new project with:

    cookiecutter cookie_project

To install the python packages, run the following command:

    poe initialize-1
    .venv/Scripts/activate
    poe initialize-2

And you can install pytorch with:

    poe force-cuda
