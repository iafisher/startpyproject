startpyproject: Generate the boilerplate for a new Python project.

startpyproject can do the following:
  - Initialize a git repo with a .gitignore that's tailored for Python.
  - Set up a pre-commit hook for git that runs black and flake8.
  - Create a flake8 configuration file.
  - Create a virtual environment.
  - Create directories for a main package and a test package.
  - Create a new Django project.

Make sure to run the script in the already-created project directory.
Typical usage is

    $ mkdir myproject
    $ cd myproject
    $ startpyproject -p mypackage

The startpyproject script is self-contained. Simply drop it anywhere on
your PATH. Run

    $ startpyproject --help

for documentation of command-line options.
