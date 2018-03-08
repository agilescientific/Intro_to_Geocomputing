# Introduction to Geocomputing

## 00 Getting ready
- 01: What and why?
- 03: The command line on your OS
- 05: Installing Python
- 10: Conda environments
- 15: Python command line
- 20: Running a .py file
- 25: The Jupyter Notebook
- 30: Modules and packages
- 35: Choosing an editor
- 40: Getting help
- 45: Resources for learning
- 50: Principles of geocomputing

## 10 Getting started in Python
- 05: Plot a topographic map
- 10: Make a 3D visualization
- 15: Calculating acoustic impedance: variables and assignment
- 18: Representing rocks: numbers
- 20: Representing rocks: text
- 25: Geological abstractions: lists
- 30: Operating on time and space: loops and if
- 25: Geological objects: passing data around with dicts
- 35: Dealing with messy data: text processing
- 40: Processing a data file: reading files
- 45: Computing elastic parameters: operators and expressions
- 50: Computing reflectivity: functions
- 55: Compiling a stratigraphic column: classes again
- 60: Computing a synthetic seismogram: bringing it all together

## 20 Numerical computing with NumPy and matplotlib
- 05: Speeding up the reflectivity calculation
- 10: A 2D wedge model
- 15: Seismic inversion
- 20: Load and inspect a well log
- 25: Making a well log class
- 30: Load and inspect a seismic section
- 35: Load and inspect a seismic horizon
- 40: Time conversion of a sonic log                                  scipy
- 45: Convolution and filtering                                       scipy
- 50: Vectorizing the synthetic seismogram                            numpy
- 55: An offset synthetic seismogram                                  bruges

## 30 Practical programming (optional... we may not be the people to write this)
- 05: Persistence
- 10: Writing code
- 15: Version control
- 20: Testing
- 25: Documentation
- 30: Packaging
- 35: Profiling and optimization
- 40: Getting better


--- 

## Practical programming

### Writing code
- Text editors, IDES, Jupyter.
- Linting and PEP8.
- Documentation, testing, continuous integration.

### Version control
- Introduction to git and GitHub.
- - clone a project that interests you, and use it.
- - start a new repo for our well log class and get it set up.

### Test driven development
- Untested code is broken code.
- Writing tests.
- - write the first tests for our well log class.

### Documentation
- Writing self-documenting code: docstrings and comments.
- Supporting documents and notebooks.
- - document our well log class.

### Packaging
- Functions, files, modules, and packages — review.
- Setup.py, requirements.txt, PyPi, and everything else.
- Managing branches in git.

### Getting better
- Tips for becoming a better programmer.
- Online resources. Conferences and meetings.

### Other
- Containers, Docker, and developer operations.


---

## Coding style

For the book, could include this too if we wanted to.

- PEP8 all the way, more or less.
- Single quotes for identifiers (eg keys), double quotes for English, including docstrings.
- Lowercase variable names, except for classes.
- Spaces around =, except never as arguments.
- Spaces around operators unless things get out of hand, and not around `**`.
- Docstrings: always.
- No side effects, except plotting and file writing are ok.
- Named tuples... probably not in this book, but I like them.
- Type hints: jury is out. I like them...
