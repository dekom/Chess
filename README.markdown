Chess
=====

Version 0.101205 - 2010, Dec 05

by Xing Zhou
<http://www.xing-zhou.net/>

Introduction
------------

Chess is my attempt at writing a chess bot in ANSI C using techniques such as BitBoards, Alpha-Beta Pruning, etc.  This project is inspired by the chess program I had to complete for an assignment for my college computer science course.  The files are accessible from [my other repository][mr], though it only contains files for the searching algorithm because I am not entitled to publish files for the board representation, engine, and interfaces that connects to a chess server run by my professor.

	[mr]: http://www.github.com/xingzhou/15211-Chess
	
Goal
----

That being said, I'm going to attempt to rewrite the entire chess-bot program in C, including the board representation, engine, and the web interface.  Given that I know other student(s) before me have done jsut that, I have faith that I could accomplish it.  Additionally, I have tons of resources at my hands because all my professors are of great help.

Implementation Details
----------------------

While researching for the chess I've done in class, I came across many algorithms that simply fascinated me, though the time limit prohibited me from implementing all of the algorithms.  Therefore, I'm going to list the algorithms and such in hopes that I could test all of them.

Algorithms:

- MiniMax
- NegaMax
- NegaMax AlphaBeta
- NegaScout
- MTD(f)
- Repetition detection
- Transposition table
- Killer/history heuristics