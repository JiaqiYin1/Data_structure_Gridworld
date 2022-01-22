# Data_structure_Gridworld
Due:  Due:  Friday, July 9 by 11:59PM
Late Policy: submissions accepted up to 24 hours late for a 10% deduction (11:59PM Sat, July 10)

Objectives:
Design and implementation of all data structures for a given specification (including runtime requirements).
More practice with linked lists (and arrays/vectors).

Summary:  you are given the specifications for an Abstract Data Type along with runtime requirements.  Your job:  design and implement a class called GridWorld which meets the requirements.

Welcome to GridWorld where everybody is a number and lives in a square (unless of course they are dead).                

The World:  The world is kind of boring.  It is an RxC grid (rows and columns).  Each entry on the grid is called a district and is referred to by its row r and column c where r∈{0..R-1} and c∈{0..C-1}.  We’ll sometimes refer to such a district as Dr,c.

The People:  Then there are the people; each person is uniquely identified by an integer ID (like a social security number).   Person IDs start at zero.  Each living person resides in one (and only one) of the districts.

Day Zero:  When a world is created, just two things determine its initial configuration:
R:  the number of rows
C:  the number of columns

When a world is created, there are no people at all:  every district is a wasteland with no population.  However, once created there are a number of operations that can be performed on the world (you should be thinking "Abstract Data Type" about now).

Operations:  once a world is created, there are various operations that can be performed.  These operations are laid out in the table starting on the next page.

C++ Stuff:  You have been given a bare-bones file GridWorld.h as a starting point.  There are no data members specified -- that is part of your job!

All of the required functions (and constructors) appear as empty "stubs".  This is a pretty "blank-slate" assignment!

Your complete implementation GridWorld.h will be the primary deliverable for the assignment.
