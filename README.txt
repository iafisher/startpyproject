startpyproject: Generate the boilerplate for a new Python project.

startpyproject does the following:
  - Initializes a git repo with a .gitignore that's tailored for Python.
  - Sets up a pre-commit hook for git that runs black and flake8.
  - Creates a flake8 configuration file.
  - Creates a virtual environment.
  - (Optional) Creates directories for a main package and a test package.
  - (Optional) Creates a new Django project.

Make sure to run the script in the already-created project directory.
Typical usage is

    $ mkdir myproject
    $ cd myproject
    $ startpyproject -p mypackage

The startpyproject script is self-contained. Simply drop it anywhere on
your PATH.
