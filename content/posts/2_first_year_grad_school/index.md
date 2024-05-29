---
title: "My first year of grad school"
date: 2024-05-28
---


<link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/katex@0.12.0/dist/katex.min.css" integrity="sha384-AfEj0r4/OFrOo5t7NnNe46zW/tFgW6x/bCJG8FqQCEo3+Aro6EYUG4+cU+KJWu/X" crossorigin="anonymous">

<!-- The loading of KaTeX is deferred to speed up page rendering -->

<script defer src="https://cdn.jsdelivr.net/npm/katex@0.12.0/dist/katex.min.js" integrity="sha384-g7c+Jr9ZivxKLnZTDUhnkOnsh30B4H0rpLUpJ4jAIKs4fnJI+sEnkvrMWph2EDg4" crossorigin="anonymous"></script>

<!-- To automatically render math in text elements, include the auto-render extension: -->

<script defer src="https://cdn.jsdelivr.net/npm/katex@0.12.0/dist/contrib/auto-render.min.js" integrity="sha384-mll67QQFJfxn0IYznZYonOWZ644AWYC+Pt2cHqMaRhXVrursRwvLnLaebdGIlYNa" crossorigin="anonymous"

    onload="renderMathInElement(document.body);"></script>

I just recently finished my first year of grad school at the University of Maryland. As I've been taking some time to recover from the madness of the spring semester, I figured it might actually be good to write a few things about my experience with it, and finally make a post on my thus-far under-utilized website! After all, an aspiring academic can always use more practice writing (at least [Matt Might says so.](https://matt.might.net/articles/successful-phd-students/))

I'm writing this to sort of give myself a big-picture view of how things went and so I can piece together the narrative of how things are going. If you read this and you find it helpful, let me know! My email is on the homepage.

---

### coursework

At UMD, first-year graduate students in the AMSC (Applied Math and Scientific Computation) program have the option of deciding between the Scientific Computing (SC) or the Applied Math (AM) track. In short, the SC track is less flexible in terms of coursework but doesn't require qualifying exams; the AM track is more flexible but requires qualifying exams. 

Being unsure, I opted for the first-year sequence of Scientific Computing I and II (which also counts as a coursework-based qualifying exam for the Applied Math track). However, ever since I'd taken (non-measure theoretic) courses on stochastic processes and real analysis in undergrad, I wanted to learn measure-theoretic probability. Convex optimization had also been a topic I'd wanted to learn since doing research that used optimization tools, so I excitedly added it to my schedule. 

Thus, my first year schedule ended up looking like this:

<center>

<style type="text/css">
.tg  {border-collapse:collapse;border-spacing:0;}
.tg td{border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;
  overflow:hidden;padding:10px 5px;word-break:normal;}
.tg th{border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;
  font-weight:normal;overflow:hidden;padding:10px 5px;word-break:normal;}
.tg .tg-u0o7{border-color:inherit;font-weight:bold;text-align:left;text-decoration:underline;vertical-align:top}
.tg .tg-0pky{border-color:inherit;text-align:left;vertical-align:top}
.tg .tg-0lax{text-align:left;vertical-align:top}
</style>
<table class="tg"><thead>
  <tr>
    <th class="tg-u0o7">Fall 2023</th>
    <th class="tg-u0o7">Spring 2024</th>
  </tr></thead>
<tbody>
  <tr>
    <td class="tg-0pky">Sci Comp I</td>
    <td class="tg-0pky">Sci Comp II</td>
  </tr>
  <tr>
    <td class="tg-0pky">Prob I</td>
    <td class="tg-0pky">Parallel Comp.</td>
  </tr>
  <tr>
    <td class="tg-0pky">Convex Opt.</td>
    <td class="tg-0pky"></td>
  </tr>
  <tr>
    <td class="tg-0lax">TA: Linear Algebra</td>
    <td class="tg-0lax">TA: Intro to Prob</td>
  </tr>
</tbody>
</table>
</center>

The fall semester was a bit of a wake-up call to some extent. Moments that I remember include:

- For Prob, I had enough background in analysis to do the problem sets after hours of struggle and StackExchange posts. But, even after that, when I got to the midterm exam and got seemingly simple questions like:<br>
    "Let \\(\eta \rightarrow a\\) and \\(\xi \rightarrow b\\) (both in probability), where \\(a,b\\) are nonzero constants, and \\(\eta,\xi\\) are zero only on a set of measure zero. Show that \\(\eta/\xi \rightarrow a/b\\) in probability." <br>
    It's trivial if you know the [continuous mapping theorem](https://en.wikipedia.org/wiki/Continuous_mapping_theorem), but we hadn't been taught that. At the end of the day we got to take it home since all of us did so badly during the in-class portion of the exam.

- In Convex Optimization, numerous topics would appear on the homework that hadn't been taught in class (e.g subgradients), and vague questions like "Would this choice of function be reasonable? Propose some conditions that would be appropriate" also appeared.

- In Sci Comp I, I did well on all the HWs through the class, only to get a B grade overall due to my grade on the final. This meant I would have to get an A or better in the subsequent classes in the sequence to get qual credit.

I initially felt frustrated by these moments. "Why hadn't we been taught these things? Why is the grading this way? Why can't this be more specific?" To some extent, though, I began to appreciate that the standard for me as a graduate student was going to have to be higher than what I had in undergrad. 

Grad students (or, at least aspiring academics) need to be capable of reading and learning on their own when they encounter problems they don't know how to solve, and quickly learn techniques for solving those problems from the appropriate references. That's how research is, after all... you are trying to solve a problem that hasn't exactly been solved before, and perhaps turn a somewhat ill-defined question into a precise mathematical statement.

Another conclusion - taking three classes is (generally) too much. I thought I could power through like I did in undergrad, but... no. Core grad courses are significantly harder, and TA duties (which did not exist in undergrad for me) also can be thought of as an additional class. During the final exam period, you not only have to take your own exams but also grade the finals of your students. I was so busy that I could not allocate the appropriate amount of effort to do well in all my classes. This has its consequences, especially when you're taking core courses that you need to do well in (see above).

I wisened up and only took 2 courses the following semester (no more excitedly adding classes to my schedule). That turned out to be better - I was able to spend more time on my core course and get the grades I needed to fulfill the qual credit requirement. Still, though, the spring semester was also stressful - the TA work turned out to be more involved than expected as compared to the previous semester. This is just since there is some variance from course to course.

--- 

### teaching/TAing

On the other hand, teaching for me has been a mix of ups and downs.

- I discovered I really love lecturing. As a TA for Linear Algebra and Intro to Prob, I only had to do 50-minute discussions sections where I reviewed the course content and did example problems. I love being able to share my insight into the topics and help the students try to get a better handle on things, and I find the challenge of presenting the problems and content in a logical and organized way to be a delight. The real-time feeling of having students in front of me while I scratch away at the chalkboard definitely also keeps me engaged.
- I love having an excuse to make awful jokes. ("Hey guys, today we're learning about the [CLT](https://en.wikipedia.org/wiki/Central_limit_theorem)... you know, chicken, lettuce, and tomato"). Sometimes they smile. Mostly they don't, because they're awful jokes. It amuses me, though.
- On the other hand, I really don't like grading. It's tedious work, and deciding on how many points to give what portion of the work can feel quite arbitrary. I also don't feel at ease when I give people bad grades; knowing that my actions can really make or break my students' days. The grading turnaround for exams is also quite tight - I had to skip some of my own classes to make the turnaround for some weeks.
- Logistically, coordinating student work for a large-lecture class (even with several TAs) can become a headache as papers need to be shuffled back and forth between offices. I became a huge fan of Gradescope for this reason.

I guess my position can be summarized as "I like the actual teaching part but not the paperwork part." That's probably a very common opinion.

---

### quals

I took one qualifying exam after my fall semester, the qualifying exam in Probability. Initially, I was somewhat apprehensive about it since I only had taken half of the required course sequence (Prob I), but I told myself "I have to try. Worst case, I fail and I have to do it again, but now I know what it's like. Best case, I pass."

I studied primarily from [Durrett's book](https://services.math.duke.edu/~rtd/PTE/PTE5_011119.pdf). I found it to be an easier read than Koralov and Sinai, which is the book used in UMD's probability courses. Compared to Koralov and Sinai, Durrett is slightly more chatty and gives more examples, which I think makes for a better exposition. If I had more time, I probably would have also looked to [Steele's book on stochastic calculus](https://link.springer.com/book/10.1007/978-1-4684-9305-4) to really nail down martingales, martingale convergence, Brownian motion, and stochastic integrals. There's some more reading to do...

I prepared by just doing as many problems from the old qualifying exams as I could. Some of them I couldn't even solve (I still don't know how to do stochastic integration). There were also no official solutions at the time I was studying, so I was sort of in the dark as to whether I was doing things right. I really should have asked some more senior students if they had answer sheets for the old exams, though...

I didn't try to waste too much time carefully learning the content. If I had more time and I knew what I was doing; it definitely would have been better to carefully read and learn - but for the exam, I tried to focus on patterns - "ok, I definitely gotta use dominated convergence for this one. ok, this one is a limit theorem question" - and just tried to get a handle on how to apply the basic tools.

Apparently it worked well enough. I got a 36/60, which was the bare minimum passing score for this exam.  But, as others told me, "nobody is going to ask what you got on the qual - it only matters that you passed." Amusingly, I also heard "that's actually optimal because it means you didn't study more than you needed to."

This result pretty much cemented my decision to follow the Applied Math track.

---

### research

I tried to get started doing research and reading papers, but it was incredibly hard to find time and energy to do so on top of both the teaching and classwork committments. I sort of get the impression that the typical path is to focus on classwork for the first two years, then transition into research, but I wanted to get right into thinking about the bigger picture as soon as possible. 

Specifically, I started reading about multi-agent reinforcement learning, which I found to be a pretty fascinating and mathematically rich area of research. I learned some basic game theory, a small smattering of some proper complexity theory, and got to realize that there are some interesting applications of probability theory and PDEs to strategic interactions. I got a teeny bit of the big picture, but I don't even completely understand that. My goal is to do some more reading this summer.

Still, I think I've learned some things about the way I tend to read papers that I need to work on. For example, I have a tendency to handwave and just hope the details work out. In other words, I'm not careful enough. This is probably a bad holdover from handwavy arguments on my homework. 

To fix this habit, I need to get into the habit of being critical and asking questions to myself. 
- "Why does this matter?" 
- "Can you prove this?" 
- "Do you really understand what this term/definition means?"

In my meetings where I would explain what I learned, I would get questions that I didn't know how to answer. I would dimly realize that I had thought about this, but not to the level that was actually sufficient to confidently and quickly answer the concerns that were raised.

---

### life

I overall had a great time hanging out with my fellow grad students - everyone in the department at UMD is quite friendly. It was honestly really great to meet everyone the first few days and hear about the diverse set of research interests and backgrounds we all had. At first, it was honestly sometimes intimidating hanging out with other students who had more comprehensive backgrounds than I did, but I quickly realized that everyone was overall pretty relaxed and accomodating. I'd always felt a bit inadequate in the sense that I didn't (and still don't) have the most comprehensive pure math background, but I realized that everyone has their own strengths and interests - and that's alright. I learned that it's better to ask questions, show interest, and find common ground (espectially outside of just math), rather than be scared that I don't know enough to hold a conversation. 


On the other hand, I became aware that some of my peers actually looked up to me in the same way that I looked up to others, which was a funny realization. It seems that no matter how highly we achieve, we're all going through similar experiences internally. That brought me back to earth. Math isn't everything; it may be a large part of my life, but not necessarily the whole world to me. At the end of the day, we're all just people connecting over shared interests and common experiences.

We had a cohort struggling through the Sci Comp I/II sequence together, which made the experience significantly more bearable. We were able to share hints and strategies for attacking some of the HW problems in our shared office, which helped us get through the weekly homework.

Just trying to also stay on top of the things that I needed to to continue living (like cooking for myself, cleaning, etc.) also took more time and energy than expected. It got somewhat demoralizing sometimes when after a long day of teaching and coursework, I remembered I had to get groceries. I also had to deal with seemingly random inconveniences like roaches and having my car damaged from a theft attempt. These were all ultimately resolvable, but felt demoralizing at the time. 

All these stressors resulted in several weeks where I had to keep telling myself "You gotta keep it together" just to make it through. It really made me realize that I actually do need to take time for myself, and spend time with the people I care about, and do the things I love besides just math. Seems obvious, right? But it was easy to forget when I was in the thick of things.

On a slightly brighter note, I took up bike commuting to save on gas and parking dollars. This year, I hit a total of 1000 miles on my electric bike, and probably more that weren't logged on my non-electric bike. I think that was a fun achievement. It also helped me get some exercise that I would have absolutely neglected if I were only commuting by car.

---

### conclusion

I went in feeling pretty hyped to do math and I came out the first year feeling pretty tired and in need of a break. That's normal; I think. At least they tell me the first year is the hardest. I don't know if I entirely believe that, but I'm willing to go along with it for now.

My lessons learned (and favorite advice for myself) from this experience so far would probably be:

- **Don't be afraid.** I wouldn't have been able to pass the quals, or learn as much as I did this year, if I remained afraid of people who knew more than me, or was scared of taking a class in something I didn't really know as well. I wouldn't have gotten started with reading if I was scared to reach out.
- **Always keep the big picture in mind.** A piece of advice from my old mentor back at UVA. I feel like this is good advice for both research and life. To write a good article, you have to know what the overarching story is. To keep going through grad school, you have to keep telling yourself a story of why you are here and why this is worthwhile. (There were many moments where I questioned why I was doing this.)
- **Be critical and careful.** To make a good story, you have to know all the details and make sure everything is right. You still have to know how all the details fit into the big picture and work at both scales.
- **A support network is critical.** Having people you can talk to when things get too hard helps immensely.
