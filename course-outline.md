# Introduction to Python for GIS Analysts
Prepared by **David O'Sullivan** 16 April 2025 for Wellington City Council City Insights GIS team

## Overview
Given the scope of materials (detailed below, per the requirements document) more than two days are needed. Even extended over that time frame this will be an intense learning experience! 

Each day should run from 9 until 5, with sessions running 9:00-11:30 (br), 12:30-2:30, 3:00-5:00. Topics in [brackets] will be covered as time permits.

## Day 1 The core Python language
Time  | Topic
-:    |:-----
**Session 1** | **LANGUAGE FUNDAMENTALS**
09:00 | **Introductions**
&nbsp;| Introduction to course environment (incl notebooks)
09:15 | **Basic concepts**
&nbsp;| Values, variables, types
&nbsp;| Operators, expressions, statements
09:45 | **Functions**
&nbsp;| Calling functions
&nbsp;| Writing functions with `def`
10:30 | _BREAK_
10:45 | **Logic and flow control**
&nbsp;| Boolean logic
&nbsp;| `if`, `else`, `elif`, `match... case...`
&nbsp;| `while` loops
&nbsp;| Example programs: `hangman.py` and `leap_year.py`
11:30 | _LUNCH_
**Session 2** | **DO IT AGAIN! SEQUENCES AND INTERATION**
12:30 | **Sequences**
&nbsp;| `list`s (_mutable_)
&nbsp;| `string`s (and `tuple`s) (_immutable_)
&nbsp;| Slicing and dicing sequences
 1:00 | **Iteration**
&nbsp;| `for` loops
 1:30 | **Dictionaries**
&nbsp;| Mapping keys to values
&nbsp;| `.keys()`, `.values()`, `.items()` 
&nbsp;| Counting stuff with a dictionary
 2:15 | **Other collections**
&nbsp;| `set`, `defaultdict`, `namedtuple`
 2:30 | _BREAK_
**Session 3**| **PUTTING PYTHON TO WORK**
 3:00 | **Some examples**, such as:
&nbsp;| Converting files: renaming, re-projecting
&nbsp;| Reading a file with `open ... as ...`
&nbsp;| Debugging code
&nbsp;| _Any other topics as suggested by the group_
&nbsp;| [Turtle graphics challenges] 
ends 5:00 |

## Day 2 Data tables and automation
Time  | Topic
-:    |:-----
**Session 1** | **INTRODUCING `pandas`**
09:00 | **Overview**
09:15 | **Getting at data**
&nbsp;| `.loc`, `.iloc` 
&nbsp;| Slicing in `pandas`
10:00 | **Cleaning data**
&nbsp;| Checking formats
&nbsp;| Fixing incorrect data
10:30 | _BREAK_
10:45 | **Applying functions**
&nbsp;| Never iterate if you can help it
11:30 | _LUNCH_
**Session 2** | **MORE `pandas` AND `geopandas`**
12:30 | **Tabular workflows**
&nbsp;| left, right, inner, and outer joins
&nbsp;| The `.groupby` operator
 1:00 | **`geopandas = pandas + geometry`**
&nbsp;| `GeoDataFrame`
&nbsp;| `GeoSeries`
 1:30 | **Simple maps with `geopandas`**
&nbsp;| Plotting data
&nbsp;| Thematic mapping
 2:00 | **GIS operations** 
&nbsp;| Unary operations: e.g., `buffer` 
&nbsp;| Binary operations: overlay and join
 2:30 | _BREAK_
**Session 3** | **USING `pandas` AND `geopandas` TO GET STUFF DONE!**
 3:00 | **Making notebooks into scripts**
&nbsp;| The basics of making a script
&nbsp;| Command line options
 3:30 | **More examples**, such as
&nbsp;| Cleaning up a spatial dataset
&nbsp;| Counting points in polygons
&nbsp;| Small multiple maps
&nbsp;| _Any other topics as suggested by the group_
ends 5:00 |

## Day 3 Spatial data (are special)
Time  | Topic
-:    |:-----
**Session 1** | **OBJECT-ORIENTED PROGRAMMING AND APIs**
 9:00 | **How things like `geopandas` work on the inside**
&nbsp;| Classes and objects
&nbsp;| Defining classes with `class`
 9:45 | **Python's 'dunder' methods**
&nbsp;| Making flexible classes pythonicly
&nbsp;| A couple of simple geometry classes 
10:30 | _BREAK_
10:45 | **The `shapely` module**
&nbsp;| Examples of code from `weavingspace`
&nbsp;| Some `shapely` gotchas
11:30 | _LUNCH_
**Session 2** | **THE WIDER `python` (GEOSPATIAL) ECOSYSTEM**
12:30 | **Other useful modules**
&nbsp;| `pysal`, `networkx`, `osmnx`
 1:15 | **From classes to APIs**
&nbsp;| Navigating a complicated API (like `pyqgis` or `arcpy`)
 2:00 | **A tip from APIs you can use every day** 
&nbsp;| Flexible function calls
 2:30 | _BREAK_
**Session 3** | **MORE COOL `python` TRICKS**
 3:00 | **'Advanced' topics in python**
&nbsp;| List comprehensions
&nbsp;| `itertools`
&nbsp;| Marimo notebooks and dashboards
&nbsp;| _Any other topics as suggested by the group_
ends 5:00 |
