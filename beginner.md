# Introduction (or How to be Better at USACO)

Recently, I’ve received a number of questions along the lines of “how do I get better at programming contests?,” or “how do I achieve X rank in Y time,” from beginners. Anyway, due to the drastic increase in new competitors I’m seeing lately, I decided to write some articles on programming olympiads, perhaps as a programming counterpart to [Evan Chen’s math blog](https://usamo.wordpress.com/), because I think it’d be helpful. My name is Darren Yao, and I'm a current competitor in the USACO Platinum division (top ~200 US). I'm also the author of the book _An Introduction to the USA Computing Olympiad_ (linked below), and the president of my school's computer science club.

By far the most common question I receive is “can I get from beginner level to Platinum in a year?” I mostly get this from beginners, and probably as a result of the fact that quarantine killed most people’s extracurricular activities, so they’re looking for some resume padding for their college applications. To answer the question: yes, it’s possible (I did it in eight months). However, if you really want to do this, you’ll need to be extremely dedicated and productive. Furthermore, you should know that if you’re only doing programming competitions out of a desire to look good on college applications, and don't actually enjoy the process, you will likely burn out and end up nowhere. Consider yourself warned. 

Welcome to the world of competitive programming! I’m going to start off by reiterating a phrase seen often on AoPS: stop looking for the “right” training. There certainly does not exist a method that will guarantee you X rank in Y amount of time, because as with all contests, there are other factors involved: luck, innate talent, efficiency and productivity of your training time, and so forth. Most importantly, everyone learns differently, and your training should be structured around your own strengths and weaknesses so that it fits _you_. That being said, I'm going to provide some useful resources below. Readers are encouraged to use their best judgement and skip around the books or go through chapters faster or slower as they see fit; in the end, it is up to you to make your own learning effective.

# USACO Divisions
The USACO has four divisions. Getting a perfect score on one division earns you an in-contest promotion, which means you can take the next division's contest right away. If you don't get a perfect score but meet the contest-dependent promotion cutoff, you are promoted to the next division for the next month's contest. Each division's topics include but are not limited to the following:
- Bronze: Simulation, brute force/complete search, implementation, intersections of 2 and 3 squares, ad-hoc problems. The general focus of the Bronze division is not on any specific techniques, but rather basic algorithmic thinking, mastery of your chosen programming language, and intuition and ability to think through problems.
- Silver: Sorting, prefix sums, binary search, graph theory, standard library data structures, implementation, ad-hoc problems. The main theme of the Silver division is applications of relatively simple algorithms. However, just because the algorithms themselves are relatively simple does not make the problems easy; in fact, silver problems require a lot of ingenuity, which makes passing silver a major bottleneck for many. Again, this is where practice comes in -- once you've done enough problems, you get much better at recognizing how you should attack any given problem.
- Gold: More graph theory (shortest-path algorithms, minimum spanning tree), tree algorithms, dynamic programming, data structures (Fenwick tree, possibly segment tree), topological sort, combinatorics and number theory. Gold features a much wider breadth of material than silver, but in my opinion requires less ingenuity and intuition, and a large number of gold problems are relatively straightforward and simple. The main thing you'll need to pass gold is knowledge of all the algorithms, and extensive practice.
- Platinum: The topics that show up on platinum contests aren't particularly well defined, and there is essentially no upper limit on problem difficulty, although this varies wildly.

# Recommended Resources 

If you don’t know how to code, you need to learn that first; this should be pretty easy to do from resources available online. The two primary languages used in competition are C++ and Java; C++ code is shorter, runs faster and is thus favored by the majority of contestants, but Java is granted extra runtime on the USACO to compensate and I personally find it more intuitive and easier to debug. At the high platinum and camp levels, using C++ is an advantage, but Java still remains viable. Python generally is not an acceptable language due to its slow runtime.

A solid background in competition math can make the learning curve easier, because you've already developed the intuition needed to solve problems. This generally allows you to get through bronze material very quickly, and also speeds up the learning of more advanced concepts. That being said, the advantage you gain from having previously done competition math is diminishing -- USACO wants to make Platinum qualification a major goal in and of itself, rather than a mere side-quest for the math contest elite.

At the bronze and silver level, you should read my book _An Introduction to the USA Computing Olympiad_, and do the accompanying practice problems at the end of each chapter. Links are below:

- [Intro to USACO, Java Edition](http://darrenyao.com/usacobook/java.pdf)
- [Intro to USACO, C++ Edition](http://darrenyao.com/usacobook/cpp.pdf)

At the gold level, resources are still in development. I would recommend just learning all the standard algorithms and then doing lots of practice problems. The site [cp-algorithms](https://cp-algorithms.com/) and certain sections of [Competitive Programmer's Handbook](https://cses.fi/book/book.pdf) provide good explanations for most algorithms, but they're unfortunately only available in C++.

For additional practice, CodeForces has an extensive selection of problems, sorted by rating, topic, or pretty much any other criterion you can think of.

# IDEs and Text Editors

Some good IDEs for competitive programming are:
- Java: Visual Studio Code or IntelliJ/Eclipse
- C++: Visual Studio Code, CodeBlocks, vim/gvim, Sublime Text.
- Do not use online IDEs that display your code publicly, like the free version of ideone. This allows other users to copy your code, and you may get flagged for cheating.

# On Exercises and Practice Problems

In general, I think it’s fine to read the solution relatively early on, as long as you’ve made several different attempts at it and you can learn effectively from the solution.
- On a bronze problem, read the solution after 15-20 minutes of no meaningful progress, after you’ve exhausted every idea you can think of.
- On a silver problem, read the solution after 30-40 minutes of no meaningful progress.
- When you get stuck and consult the solution, you should not read the entire solution at once, and you certainly shouldn’t look at the solution code. Instead, it’s better to read the solution step by step until you get unstuck, at which point you should go back and finish the problem, and implement it yourself. Reading the full solution or its code should be seen as a last resort.

Problems that you practice with should be of the appropriate difficulty. You don't necessarily need to complete all the exercises at the end of each chapter, just do what you think is right for you. A problem at the right level of difficulty should be one of two types: either you struggle with the problem for a while before coming up with a working solution, or you miss it slightly and need to consult the solution for some small part. If you instantly come up with the solution, a problem is likely too easy, and if you're missing multiple steps, it might be too hard.

# Some Final Notes
[This](https://web.evanchen.cc/FAQs/raqs.html) and [this](https://usamo.wordpress.com/2019/01/31/math-contest-platitudes-v3/) are two blog posts by Evan Chen that I find quite insightful. They discuss such things as time management, the problem-solving process, and other tips that you may find useful. 

There is also a [USACO Discord Server](https://discord.gg/bessMBe) (not affiliated with the USACO organization) for such purposes as post-contest discussion, and asking for help.

I think this is all that I wanted to say, so I’ll leave off here. Best of luck!
