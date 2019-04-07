startpyproject: Auto-generate a boilerplate Python project.

Does the following:
  - Initializes a git repo with a Python-tailored .gitignore.
  - Sets up a pre-commit hook for git that runs black and flake8.
  - Creates a flake8 configuration file.
  - Creates directories for the main package and the test package.
  - Creates a virtual environment.

Make sure to run the script in the already-created project directory. Typical
usage is

    $ mkdir my-python-project
    $ cd my-python-project
    $ startpyproject my_package_name

The startpyproject script is self-contained. Simply drop it anywhere on your
PATH.
