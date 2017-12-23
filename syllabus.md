# ECON546 - Spring 2018
- [ECON546 - Spring 2018](#econ546---spring-2018)
    - [Monetary Theory and Policy](#monetary-theory-and-policy)
    - [Course Materials and Communications](#course-materials-and-communications)
    - [Grading](#grading)
    - [Programming Language Choice](#programming-language-choice)
    - [Optional Problems and PhD Letters](#optional-problems-and-phd-letters)
    - [Course Outline](#course-outline)

## Monetary Theory and Policy
This is a graduate macroeconomics topics course with an emphasis on practical skills for empirical macroeconomics/monetary economics research and practice.  We will cover a number of applications of macro-theory to monetary economics and macro-finance.  The broad goal to is build tools to conduct macro research: creating models, and solving them on the computer.  As central banks and policy makers often use New-Keynesian dynamic stochastic general equilibrium (DSGE) models for analysis, one  of the main goals will be to understand how the ``New Keynesian'' model is constructed and simulated/solved/estimated.  The other primary goal is to build an understanding of various modeling approaches and trade-offs used in macroeconomics research through presenting a variety of models stripped down to their essentials.

- **Instructor:** jesse.perla@ubc.ca
- **Office Hours:** Thursday 10am-12pm in Iona 206
- **Prerequisites:** Graduate macroeconomics 
	- A little programming experience is very valuable, but you will be able to fill in the blanks with some hard work.
- **Textbook:** The following are not required, but worth owning:
	- **Recursive Macroeconomic Theory**: }(2012), 3rd edition, Lars Ljungqvist and Thomas J. Sargent - Useful for understanding neoclassical growth, real business cycles, search, Kalman filter, etc.  Every graduate macro-economist should own it.
	- **Monetary Theory and Policy** (2017), 4th edition, Carl E. Walsh - Masters-student oriented.  Good for topics on money-in-utility, nominal pricing frictions, the ``New Keynesian'' model, optimal monetary policy, etc.
	- **QuantEcon**: We will be following a subset of the online textbook https://lectures.quantecon.org/jl/ for part of the course
- **Learning Environment:** Come to class on time.   No cellphones.

## Course Materials and Communications
All materials will be provided online:
- Class Materials: https://github.com/ubcecon/ECON546_2018
- Communications, Announcements, and Grades: http://canvas.ubc.ca

## Grading
This is intended to be a hands-on course, with a very high workload, but there will be no in-class exam.  The grade will be based on:

- 6-10 problem sets/take home exams: 65%
	- The problem sets will not have equal weighting, and some will be short
- Final data project: 20%
	- Document "Just one fact" from a set of data-sets I give you.
	- 2-3 tight pages
- Short referee report (from a list of approved journals): 15\%
	- 2-3 pages
- PhD students: 1 guest lecture, and I expect you to complete many of the extra problems.

A word of warning: if you have never taken a class with a lot of programming assignments, it is a great deal of work, but ultimately very rewarding.

## Programming Language Choice

In this class, you will have the choice to use: Julia, Python (or Matlab if absolutely required).  My preference is that you use Julia where possible.  It is sometimes painful, but a better investment of time than learning the others.

For the computational parts of the course, the lectures notes are available in both [Python](https://lectures.quantecon.org/py/) and [Julia](https://lectures.quantecon.org/jl/), and you will have the choice of which language to use.  However, I will use Julia myself and neither the TA nor I will be able to help you with python programming.

When you are deciding on the language (which you can switch at will, or submit assignments in both!) consider that Julia is both less mature, but much more promising.  If you were just planning on using these skills in the next 6 months then Python is the best choice, but over the next 2-5 years it is worth the pain to learn Julia earlier.  See [Python vs. Julia](https://lectures.quantecon.org/about_lectures.html#python-or-julia) for more details.

To get started, go to https://github.com/econtoolkit/julia for more instructions.  You should be able to do your coursework on python or julia hosted webservices (i.e. http://next.juliabox.com and https://pims.syzygy.ca) rather than installing any software.

## Optional Problems and PhD Letters

On most of the problem sets, there will be a few `optional' problems.  You can get a very good mark in the class without doing any of these problems, but do not expect an A+ on assignments if you don't attempt them.  

Furthermore, if you are a MA student interested in getting a PhD in Economics or Finance -and want the option of having me as a letter writer - you should try to solve all of the extra credit problems as it greatly helps when I write letters.

## Course Outline

-  Linear Gaussian state space models
	-  First-order linear difference equations
	-  Transversality, bubbles, and the connection to ODEs
	-  Deterministic Linear state space models
	-  Stochastic Linear state space models
	-  Linear Quadratic Gaussian Control and certainty equivalence

-  Computational and analytical components of macro and DSGE models
	-  Stationarity, Log-linearization, and other techniques
	-  Neoclassical growth and RBC into linear Gaussian systems
	-  Building general equilibrium models on the computer
	-  Impulse response functions
	-  Dixit-Stiglitz algebra, monopolistic competition, and price indices

-  Monetary economics and policy
	-  Models with money in utility (MIU)
	-  Monetary neutrality and super-neutrality
	-  Simple models of nominal price frictions
	-  The New Keynesian DSGE model (i.e., RBC + MIU + nominal frictions)
	-  Time consistency of optimal monetary policy (Gaussian Linear-Quadratic framework)

- Continuous-time methods in macro and monetary economics
	- Cook-book stochastic processes and dynamic programming problems
	- Monetary search and models of liquidity
	- Optimal stopping in continuous-time and variational-inequalities
	- Simple models with heterogeneous firms and steady-state distributions.