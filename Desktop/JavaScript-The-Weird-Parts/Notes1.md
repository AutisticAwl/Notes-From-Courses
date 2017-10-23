# Syntax Parser#
A program that reads your code and determines what it does and if its grammar is valid.

#Lexical Environment#
Where something sits physically in the code you write.
- 'Lexical' means having to do with words or grammar.
- **Where** you write something is _important_.

#Execution Context#
A wrapper to help manage the code that is running.

#Name/Value Pair#
A name which maps to a unique value.
- Name may be defined more than once, but only one value at any given **Context**.

#Object#
A collection of Name/Value Pairs.
- Simplest definition in **JavaScript**.

#Global#
"Not inside a function."

##Execution Context is Created##
Global Object		‘this’			Outer Environment 
	Setup Memory Space for Variables and Functions
			#”Hoisting”#

##Execution Context Runs Code##
Global Object		‘this’			Outer Environment
		Runs Your Code 

#Single Threaded#
One command at a time. 

#Synchronous#
One at a time. 

#Invocation#
Running a function. 
_By using ()._	
						