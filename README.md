# FamilyTree

Problem Statement: Design a family-tree to track relationships among people. The goal is to be able ask following questions:
Are the given two people related? (e.g. Uncle-nephew relationship)
Are the given two people related by blood? (e.g. Brother-in-law is NOT a blood relationship)
How far-removed are the two people in their relationships? (Parent-child relationship is a direct, degree-0 relationship, whereas Uncle-nephew is a degree-1 relationship.)
Problem Description: 
The goal is to come up with a suitable in memory data structure to store the family tree. Clean APIs should be provided to load entries into the family tree(s) and a good algorithm(s) to answer some/all of the above questions.

The expectation is that the submitted code compiles (under reasonable assumptions of OS/compilers/memory constraints etc), data can be loaded, and the above API routines invoked. An API and implementation for deleting data is a plus. 

Even though optimized algorithms and implementations are preferred, the focus should be on correctness, completeness of implementation and well-written and well-documented code. Unit tests are a plus.

Some simplifying assumptions are allowed:

Folks can be married at most once and only to a member of the opposite sex, any child is produced only from married couples, no divorce.

Note that we're looking for relationship between people but we don't expect printouts like "Second cousin twice removed" -- just are two people related, degree of relationship, and are they related by blood or not.
