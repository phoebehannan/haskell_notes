# Chapter 2:Hello, Haskell!

## 2.1 Hello, Haskell

* GHC is the Glasgow Haskell Compiler. It is written in Haskell and C and turns
  Haskell code into x86(processors) or ARM executables(decodes).

* GHCi is the interactive mode, or REPL.

## 2.2 Interacting with Haskell code

* REPL stands for Read Eval Print Loop, and it reads code you type into a
  command line shell, evaluates it, prints the result, and then loops so you can
  type in more code.

* Haskell offers two primary wasys to input code; through GHCi or typing it into
  a text editor and then loading it into a source file into GHCi

* prelude is a library of standard functions that are automatically loaded when
  opening GHCi or Stack GHCi. it can be turned off.

* Commands that GHCi understands begin with the : character

* Most commands can be abbreviated to the first letter

* :: is a way to write down a type signature

## 2.3 Understanding expressions

* *Expressions* may be values, combinations of values, and/or functions applied
  to values

* All of Haskells expressions work in a similar way to doing arithmatic,
  evaluating to a result in a predictable and transparant manner.

* *Declarations* are top level bindings which allows us to name expressions.

* *Normal form* is used to describe expressions that have no more evaluation
  steps that can be taken, or when they've reached an irreducible form.

* Reducible expressions are also called *redexes*.

## 2.4 Functions

* *Functions* are a specific type of expression. Functions in Haskell are
  related to functions in mathmatics, they map an input to an output.

* *argument* is the input for a function.

* In Haskell, when it seems we are passing multiple arguments to a function, we
  are *actually* applying a series of nested functions, each to one argument.
  This is called *currying*

## 2.5 Evaluation

* *normal form* is when there are no reducible expressions left.

* *parameter* has two meanings. formal parameter is the variable as found in the
  function definition, and actual parameter is the actual input supplied at
  function call.

* "function definiton" is the naming of a function. "function call" is when you
  apply a function to some arguments. the function is only called if it is
  transforming an input. 

## 2.6 Infix Operators

* Functions in Haskell default to prefix syntax. Functions being applied are at
  the beginning of expressions rather than in the middle, or infix.

* Operators are functions which can be used infix style. All operators are
  functions but not all functions are operators. (`*`,`-`,`+`,`/`) are all examples of
  operators.

* adding ticks to the functions name sometimes allows you to use them infix style,
  and wrapping operators in parenthesis sometimes allows you to use them prefix
  style.

* *precedence* is where the implicit parentheses are. it is only relevant if you
  do not include parentheses. (PEMDAS) 

* *associativity* means that the order of operands does not change the result.
  it can either be left to right or right to left. multiplication is left to
  right while exponents are right to left.
