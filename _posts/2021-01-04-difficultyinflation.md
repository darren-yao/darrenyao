---
layout: post
title: Olympiad Difficulty Inflation
date: 2021-01-04 
usemathjax: true
---

It's a well known fact that olympiads get harder over time. The rate of difficulty inflation varies, but it always happens.

For example, see Problem 1 from the first International Math Olympiad in 1959.

Prove that this fraction is irreducible for every natural number \\(n\\): \\[ \frac{21n+4}{14n+3} \\] 

If you know the Euclidean algorithm, this problem takes about 30 seconds to solve. This is much easier than a midrange AMC 12 question now, and the AMC 12 is an open exam that doesn't require you to be in the top 6 of your country to take it. 

At least in math, the increase in difficulty happens slowly and gradually over time. 

We now visit the realm of computer science for a more egregious example. For reference, the USA Computing Olympiad (USACO)'s Platinum division is roughly the top 200 pre-college competitors and is analogous to the USAMO; USACO Silver, while invitational, is roughly comparable to the AMC 12 in terms of difficulty. 

The [following problem](http://usaco.org/index.php?page=viewproblem2&cpid=600) appeared in a USACO Platinum contest in January 2016. The techniques used to solve this problem are two-dimensional prefix sums with a sliding window algorithm, and the intuition needed to come up with the solution isn't particularly difficult. 

Meanwhile, look at [this problem](http://usaco.org/index.php?page=viewproblem2&cpid=1063) from USACO Silver in December 2020. While the intuition isn't super difficult here either, the techniques used are similar: two-dimensional prefix sums with coordinate compression and a couple other observations. 

You can probably tell that the contest has gotten much harder because two problems of roughly similar difficulties ended up in different divisions of the contest over a time span of five years. 

So what might be the cause of this difficulty inflation? 

### More students / awareness

The first reason is that these contests are simply becoming much more well known, and more students are taking them. Let's again look at the example of USACO. In December 2015, USACO reports that 3784 unique students logged into the contest. Five years later, in December 2020, this number rose above 10,000. Despite this increase in participants, the number of students in the Platinum division has remained relatively constant. Therefore, there are more students competing for the same number of spots. If the difficulty were to remain the same, the number of students qualifying for a given division would scale linearly with the number of participants. Because of this, the competition must become more and more difficult every year. 

In the math competitions of AMC/AIME, the total number of participants has actually been going down in recent years: 44250 students took the AMC 12A in 2016, 28327 students in 2018, and 24360 students in 2020. So why has the difficulty continued to go up even as the number of competitors dropped? The easiest explanation is that the _number of students who take these contests seriously_ has continued to go up, but less students are being forced to take the exam by their schools. A large number of students who choose not to do math competitions instead participate in the other olympiads. 

It's probably expected that the other major science subject olympiads (physics, chemistry, and biology) are following the same trend as USACO. The USA Biology Olympiad has acquired a reputation for being heavily based around memorization, which unfortunately leads many students to participate in it solely for the purpose of resume-padding for their college applications. But we'll get to this later. 

### Olympiad community / culture

Some schools and geographical regions have developed particularly strong communities around olympiads, which leads to a culture that encourages younger students to participate. Examples include many parts of the Bay Area, a couple schools in San Diego, all the specialized schools in New York City, TJHSST, the Princeton and West Windsor areas in New Jersey, and so forth. Essentially, once the top competitors in each school or region become well known, the younger students seek to replicate their successes. This becomes a positive feedback loop.

At my high school, which is a competitive public school in the Bay Area, we have schoolwide math contests during lunch from the Atlantic-Pacific or California Math League (CAML) contests. Teachers incentivize students to participate with extra credit points, or outright require the contests. On top of this, the teachers maintain a cumulative ranking of student scores, which is printed out and posted in the back of some math classrooms. At the end of the year, math awards are given out, ranging from simple certificates for earning A+ grades in math courses, to the top awards: in each grade level, the top student (determined by a combination of schoolwide contest scores, AMC/AIME scores, and performance in and level of math courses) receives a "Most Outstanding Math Student in Grade" trophy and the next four receive "Outstanding Math Student" medals. Finally, there's a "Most Exceptional Performance in Mathematics" trophy given to the top math student out of the 2200ish students _in the school_. (This is the technical name for the award. Students have nicknamed it after a legendary student in the class of 2018 who won the award in all four years of high school).

Anyway, all of this explains the impact of students' environment on contest participation. At a high school like mine, students in the advanced math track are drawn towards contests from day one; obviously, this has led more students to take math competitions than they otherwise would've.

### More resources

As the number of participants increases, so does the number and quality of training resources for these olympiads. The Art of Problem Solving books are the gold standard for math competition prep, while Physics has HRK and Morin, and Biology has the Campbell textbook. As more students study off these well-known resources, the contest problems become less about pure knowledge of the subject and more about intuition and problem-solving. 

This also reduces student attrition during the studying process. USACO is the best example of this: without good resources, many students got frustrated and quit early, often as early as their first problem when they couldn't figure out how to use file input/output. It's too early to tell what impact the new resources have had on USACO's difficulty, but the second derivative of contest difficulty is positive, which seems to indicate that those of us creating studying resources have done a good job.)

### College admissions pressure

I joined an olympiad-related discord server a while ago, which was mostly made up of underclassmen and even middle schoolers. The first thing I noticed was that chat discussion would often revolve around the value of certain olympiad awards in college admissions and how to best optimize one's time towards this goal. In fact, the younger generation of olympiad participants are driven much more by college than their predecessors. This is not particularly surprising; as college admissions become more competitive, students have to work harder. 