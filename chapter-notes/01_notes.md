# Chapter 1: All You Need is Lambda

## 1.2: What is functional programming?

**Functional Programming**: "a type of programming language that relies on
functions modeled on mathematical functions"

* Functional programming languages are all based in the lambda calculus.

* Programs are a combinarion of expressions

* Expressions include concrete values, variables, and also functions

* Functions are expressions that are applied to an argument or input.

* In Haskell, Functions are *first class*: meaning they can be used as values or
  passed as arguments, inputs, and mire functions.

* Haskell does not incorporate features into the language that aren't
  translatabel into lambda expressions. This is what makes it *pure*.

* functions are relations between input sets and output sets. Each input has
  only one output.

* Purity is more properly called *referential transparency*.

* Referential transparency (purity) means that the same function will always
  return the same result when given the same values to evaluate.


## 1.3 What is a Function

**Function**: "a function is a relation between a set of possible inputs and a
set of possible outputs."

* Functions define and represent the relationship

* Functions are only valid if the output is predictable given the same input.
  Funtions can have the same output for more than one input.

* Lambda Calculus is a model of computation based on building, applying, and
  evaluating functions.

* Lambda expressions are functions buit using lambda calculus

* Computational functions are functions that can be turned into a machine

## 1.4 The Structure of Lambda Terms

* Lambda calculus has three basic components called *lambda terms*

* *Expression* refers to a superset of expresssions, variables, and
  abstractions. The simplest expression is a single variable.

* *Abstractions* are *functions* with an *argument* as an input value. written
  as a lambda expression with a head (a lambda) and a body.

* The head names the parameter of the function.

* The body tells you what to do with the parameter, when the abstraction is
  applied.

* *Bound variables* are terms that occur in both the head and the body. *unbound
  variables* only appear in the body (free variables)

* Alpha equivalence is a form of equivalence between lambda terms. This means
  that the specific symbols in the head may be replaced as long as the
  replacement is total and consistent throughout the head and body.

## 1.5 Beta Reduction

* Beta reduction is an abstraction evaluated by replacing all of its bound
  variables with the expression the abstraction is evaluated against, and then
  removing the head of the abstraction.

* Free variables are variables that are not named in the head.

## 1.6 Multiple arguments

* *currying* is when functions that require multiple arguments have multiple
  nested heads. 

## 1.7 Evaluation is Simplification

* *beta normal form* is when an expression cannot be reduced further through
  beta reduction, and means the expression is fully evaluated.

## 1.8 Combinators

* Combinators are lambda terms with no free variables and *combine* the
  arguments they are given. (\x.x and \xy.x are combinators, while \x.xy is not)

## 1.9 Divergence

* divergence meas that the reduction process never terminates or ends. This
  means that the expression can never reach *beta normal form* Eg (\x.xx)
  (\x.xx) creates an infinite loop.

## 1.10 Summary

* "Functional programming is basedc on expressions that include variables or
  constant values, expressions combined with other expressions, and functions."

* "Functions have a head and a body and are those expressions that can be
  applied to arguments and reduced, or evaluated, to a result."

* "Variables may be bound in the function declaration, and every time a bound
  variable shows up in a function, it has the same value."

* "All functions take one argument and return one result."

* "Functions are a mapping of a set of inputs to a set of outputs. Given the
  same input, they always return the same result."

  

