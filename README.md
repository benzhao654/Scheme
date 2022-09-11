# Scheme
Final project for Berkeley CS 61A: Structure and Interpretation of Computer Programs, taken during summer 2021

Interpreter for a subset of the Scheme language, built using python
To start an active interpreter session, run scheme.py
scheme.py can also take in an input file by passing the file name as a command line argument: "python3 scheme.py tests.scm"

File Descriptions:
scheme.py: implements the REPL and a evaluator for Scheme expressions
scheme_reader.py: implements the reader for Scheme input. The Pair class and nil definition can be found here.
scheme_tokens.py: implements the tokenizer for Scheme input
scheme_builtins.py: implements built-in Scheme procedures in Python
buffer.py: implements the Buffer class, used in scheme_reader.py
ucb.py: utility functions for use in 61A projects
questions.scm: contains skeleton code for Phase III
tests.scm: a collection of test cases written in Scheme
ok: the autograder
tests: a directory of tests used by ok
mytests.rst: a file where you can add your own tests
