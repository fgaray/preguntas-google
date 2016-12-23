#Google Software Engineering Interview#

This document is meant to help you prepare for your upcoming Software Engineering Interview. Keep in mind that Google takes an academic approach to the interviewing process: we are interested in your thought process, your approach to problem solving, and your skills in algorithms, coding, and performance.

##To prepare you for the interview and answer any additional questions, please review the following##
* [Great blog post on what to expect and how to prepare**](http://xrds.acm.org/article.cfm?aid=2539270)
* [Interviewing at Google](http://www.youtube.com/watch?v=w887NIa_V9w)
* [How to Get Hired by Dan Kegel](http://www.kegel.com/academy/getting-hired.html)
* [Five Essential Phone Screen Questions by Steve Yegge (Google Engineer)](https://sites.google.com/site/steveyegge2/five-essential-phone-screen-questions)
* [Binary Search](http://en.wikipedia.org/wiki/Binary_search)
* [Project Euler](http://projecteuler.net/)
* [Google+ Technical Interview Coaching Session (Recommended!)](http://www.youtube.com/watch?v=oWbUtlUhwa8&feature=youtu.be)

## Books
* [Cracking the Coding Interview (Recommended)](http://books.google.ch/books?id=nlgWywAACAAJ&dq=Cracking+the+Coding+Interview&hl=en&sa=X&ei=hUTtUfXVCoSg4gS5v4C4BQ&ved=0CDgQ6AEwAg) 
* [Programming Interviews Exposed: Secrets to Landing Your Next Job](http://books.google.ch/books/about/Programming_Interviews_Exposed.html?id=9_by-rpCSSUC&redir_esc=y)
* [Programming Pearls by Jon Bentley](http://books.google.ch/books/about/Programming_Pearls_2_E.html?id=vyhrriC6qcEC&redir_esc=y)
* [Introduction to Algorithms by Thomas H. Cormen](http://books.google.ch/books/about/Introduction_to_Algorithms.html?id=VK9hPgAACAAJ&redir_esc=y)

##Online resources##
* [Google Spanner: Google's Globally-Distributed Database]()
* [Google Chubby](http://research.google.com/archive/chubby.html)
* [Google Education: Guide for Technical Development](http://www.google.com/edu/tools-and-solutions/guide-for-technical-development/index.html)



##Areas that may be covered during your interview:##

###Algorithm Design / Analysis###
* Big-O analysis: You need to know Big-O. It's a must. If you struggle with basic big-O complexity analysis, then you are almost guaranteed not to get hired. It's, like, one chapter in the beginning of one theory of computation book, so just go read it. You can do it.
* Sorting and hashing
* Handling obscenely large amounts of data
Types of algorithm questions Google asks: [Top Coder Tutorials](http://www.topcoder.com/tc?d1=tutorials&d2=alg_index&module=Static)

Book to review basic algorithms: Introduction to the Design and Analysis of Algorithms by Anany Levitin

###Coding###
Google Engineers primarily code in C++, Java, or Python. We will allow you to use your choice of one of these language during your interview. For phone interviews, you will be asked to write code real time in Google Docs.
* Construct / traverse data structures
* Implement system routines
* Distill large data sets to single values
* Transform one data set to another

###Sorting:###
Know how to sort. Don't do bubble-sort. You should know the details of at least one n*log(n) sorting algorithm, preferably two (say, quicksort and merge sort). Merge sort can be highly useful in situations where quicksort is impractical, so take a look at it.  

###Hashtables:###
Hashtables are arguably the single most important data structure known to mankind. You absolutely have to know how they work. You should be able to implement one using only arrays in your favorite language, in about the space of one interview

###Trees:####
You should know about trees. Know basic tree construction, traversal and manipulation algorithms. You should be familiar with binary trees, n-ary trees, and trie-trees at the very least.

You should be familiar with at least one flavor of balanced binary tree, whether it's a red/black tree, a splay tree or an AVL tree. You should actually know how it's implemented.You should know about tree traversal algorithms: BFS and DFS, and know the difference between inorder, postorder and preorder.

###Graphs###
There are three basic ways to represent a graph in memory (objects and pointers, matrix, and adjacency list), and you should familiarize yourself with each representation and its pros and cons. You should know the basic graph traversal algorithms: breadth-first search and depth-first search. You should know their computational complexity, their tradeoffs, and how to implement them in real code. If you get a chance, study up on fancier algorithms, such as Dijkstra and A*, They're really great for just about anything, from game programming to distributed computing to you name it. You should know them.

###Other data structures###
You should study up on as many other data structures and algorithms as you can. You should especially know about the most famous classes of NP-complete problems, such as traveling salesman and the knapsack problem, and be able to recognize them when an interviewer asks you them in disguise. Find out what NP-complete means.

###Math###
Some interviewers ask basic discrete math questions. This is more prevalent at Google than at other companies because we are surrounded by counting problems, probability problems, and other Discrete Math 101 situations. Spend some time before the interview refreshing your memory on (or teaching yourself) the essentials of combinatorics and probability. You should be familiar with n-choose-k problems and their ilk – the more the better.

###System Design###
* Feature sets
* Interfaces
* Class hierarchies
* Designing a system under certain constraints
* Simplicity and robustness
* Tradeoffs

###Open-Ended Discussions###
* Biggest challenge faced
* Best / worst designs seen
* Performance analysis and optimization
* Testing
* Ideas for improving existing Google products

###Other things to check out###
Google Products
Google Labs
Industry News: Search Engine Land

#Helpful tips for the interview#

* Many of the questions asked in Google interviews are open-ended because our engineers are looking to see how you engage the problem.  Be sure to talk through your thought process about the questions you are asked, as well as your approach to problems and solutions.  Clarifying questions are encouraged as they showcase your thought process and approach. Think out loud!

* Our interview style may differ from what you've experienced elsewhere, and tends to be highly technical.  The interviewer will be interested in the specifics of your past projects, implementations and how you arrived at your conclusions.  Your phone interview will cover data structures and algorithms (i.e. Big-O Notation).  You will be asked to write code.

* Think about ways to improve the solution you'll present.  In many cases, the first answer that springs to mind may need some refining.  It is worthwhile to talk about your initial thoughts to a question.  A brute force explanation will be received less well than taking time to compose a more efficient solution.
