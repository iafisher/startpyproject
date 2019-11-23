startpyproject: Generate the boilerplate for a new Python project.

startpyproject can do the following:
  - Initialize a git repo with a .gitignore that's tailored for Python.
  - Set up a pre-commit hook for git that runs black and flake8.
  - Create a flake8 configuration file.
  - Create a virtual environment.
  - Create directories for a main package and a test package.
  - Create a new Django project.

Example uses:

    # Create a project in a new directory.
    $ startpyproject myproject

    # Initialize a project in the current directory.
    $ startpyproject

    # Create a Django project.
    $ startpyproject --django mysite

    # Get help.
    $ startpyproject --help

The startpyproject script is self-contained. Simply drop it anywhere on
your PATH.
