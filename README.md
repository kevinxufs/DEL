The aim of this project is to be able represent various kind of dynamic
epistemic logics and in particular to implement their epistemic action operator.

Dynamic epistemic logic is the study of information change. In
particular we are interested in how the knowledge state of an agent (i.e. what
the agent knows) changes when something happens. The meaning of 'something
happens' depends on the specifics of the logic. Each logic is equipped with
an epistemic action which has a defined effect on knowledge states.

The most basic dynamic epistemic logic is 'public annoucement logic'. This
is equipped with the epistemic action of 'public announcement'. Broadly
speaking, if phi is publically announced, then all agents update their knowledge
states to have phi being true. It is as if all agents learnt about phi via a
'public announcement'.

The initial goal in this project is to create a piece of software that is
able to implement (in public announcement logic) the following two examples:

Public announcement of an atomic proposition, p

Public announcement of the formula 'q and it is not known that q'

-- Structure

I suspect we will first need to represent the idea of a model in public
announcement logic.

A model, M = <A, W, R, V>
