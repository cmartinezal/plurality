# plurality
Program in C that runs a plurality election. CS50 Problem Set 3.


## Problem to Solve

Elections come in all shapes and sizes. In the UK, the Prime Minister is officially appointed by the monarch, who generally chooses the leader of the political party that wins the most seats in the House of Commons. The United States uses a multi-step Electoral College process where citizens vote on how each state should allocate Electors who then elect the President.

Perhaps the simplest way to hold an election, though, is via a method commonly known as the “plurality vote” (also known as “first-past-the-post” or “winner take all”). In the plurality vote, every voter gets to vote for one candidate. At the end of the election, whichever candidate has the greatest number of votes is declared the winner of the election.

For this problem, you’ll implement a program that runs a plurality election.

<img width="332" alt="Screenshot 2024-01-17 at 14 23 18" src="https://github.com/cmartinezal/plurality/assets/84383847/87f37c27-e2fb-4384-8a88-38cab7567fe2">


## How to Test

Be sure to test your code to make sure it handles…

- An election with any number of candidate (up to the MAX of 9)
- Voting for a candidate by name
- Invalid votes for candidates who are not on the ballot
- Printing the winner of the election if there is only one
- Printing the winner of the election if there are multiple winners

## Getting Started

Let's start to use this project.

## Prerequisites

A compiler for C must be installed

## Installation

To execute the project open the terminal and go to the project folder. Then compile the code with a C compiler and execute the file generated:

```sh
make plurality
./plurality
```
