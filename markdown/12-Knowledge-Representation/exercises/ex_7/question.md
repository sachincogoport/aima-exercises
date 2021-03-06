[Exercise 12.7](ex_7/)

(Adapted from an example by Doug Lenat.) Your mission is to capture, in
logical form, enough knowledge to answer a series of questions about the
following simple scenario:

> Yesterday John went to the North Berkeley Safeway supermarket and
> bought two pounds of tomatoes and a pound of ground beef.

Start by trying to represent the content of the sentence as a series of
assertions. You should write sentences that have straightforward logical
structure (e.g., statements that objects have certain properties, that
objects are related in certain ways, that all objects satisfying one
property satisfy another). The following might help you get started:

-   Which classes, objects, and relations would you need? What are their
    parents, siblings and so on? (You will need events and temporal
    ordering, among other things.)

-   Where would they fit in a more general hierarchy?

-   What are the constraints and interrelationships among them?

-   How detailed must you be about each of the various concepts?

To answer the questions below, your knowledge base must include
background knowledge. You’ll have to deal with what kind of things are
at a supermarket, what is involved with purchasing the things one
selects, what the purchases will be used for, and so on. Try to make
your representation as general as possible. To give a trivial example:
don’t say “People buy food from Safeway,” because that won’t help you
with those who shop at another supermarket. Also, don’t turn the
questions into answers; for example, question (c) asks “Did John buy any
meat?”—not “Did John buy a pound of ground beef?”

Sketch the chains of reasoning that would answer the questions. If
possible, use a logical reasoning system to demonstrate the sufficiency
of your knowledge base. Many of the things you write might be only
approximately correct in reality, but don’t worry too much; the idea is
to extract the common sense that lets you answer these questions at all.
A truly complete answer to this question is *extremely*
difficult, probably beyond the state of the art of current knowledge
representation. But you should be able to put together a consistent set
of axioms for the limited questions posed here.

1.  Is John a child or an adult? \[Adult\]

2.  Does John now have at least two tomatoes? \[Yes\]

3.  Did John buy any meat? \[Yes\]

4.  If Mary was buying tomatoes at the same time as John, did he see
    her? \[Yes\]

5.  Are the tomatoes made in the supermarket? \[No\]

6.  What is John going to do with the tomatoes? \[Eat them\]

7.  Does Safeway sell deodorant? \[Yes\]

8.  Did John bring some money or a credit card to the supermarket?
    \[Yes\]

9.  Does John have less money after going to the supermarket? \[Yes\]
