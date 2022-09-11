# Scheme
Final project for Berkeley CS 61A: Structure and Interpretation of Computer Programs, taken during summer 2021

Interpreter for a subset of the Scheme language, built using python<br />
To start an active interpreter session, run scheme.py<br />
scheme.py can also take in an input file by passing the file name as a command line argument: "python3 scheme.py tests.scm"

File Descriptions: <br />
scheme.py: implements the REPL and a evaluator for Scheme expressions <br />
scheme_reader.py: implements the reader for Scheme input. The Pair class and nil definition can be found here. <br />
scheme_tokens.py: implements the tokenizer for Scheme input <br />
scheme_builtins.py: implements built-in Scheme procedures in Python <br />
buffer.py: implements the Buffer class, used in scheme_reader.py <br />
ucb.py: utility functions for use in 61A projects <br />
questions.scm: contains skeleton code for Phase III <br />
tests.scm: a collection of test cases written in Scheme <br />
ok: the autograder <br />
tests: a directory of tests used by ok <br />
mytests.rst: a file where you can add your own tests <br />
