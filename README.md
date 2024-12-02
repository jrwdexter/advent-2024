# Advent of Code 2024

This is my personal repo for some [advent of code](https://adventofcode.com/2024) shenanigans. Just trying a few, we'll see if I finish it out.

## Requirements

Right now, my answers are built in Python. I'm using a simple virtualenv with a `requirements.txt` file. So you should be able to easily install using one of two options.

### Setting up Virtualenv

#### Option 1 - Using Direnv (Recommended)
If you have [Direnv](https://github.com/direnv/direnv) installed, just `direnv allow` in this root directory, and the virtual environment should be created for you.

#### Option 2 - Manually
Simply run:

* One time: `python -m venv venv`
* Whenever you want to work on the project: `source venv/bin/activate` (or whatever venv activation script you use)

### Installing Dependencies

`pip install -r requirements.txt`

## Puzzles

Each puzzle is contained within its day folder, and the notebook should have both parts.
