---
title       : Self-Check Questions (ungraded)
subtitle    : Discrete pdf
author      : Aidong Adam Ding
job         : Made using Slidify in R. (Click mouse then right arrow key for next slide.)
framework   : io2012        # {io2012, html5slides, shower, dzslides, ...}
highlighter : highlight.js  # {highlight.js, prettify, highlight}
hitheme     : solarized_dark      # 
widgets     : [mathjax, quiz, bootstrap]            # {mathjax, quiz, bootstrap}
mode        : selfcontained # {standalone, draft}
knit        : slidify::knit2slides
--- &multitext
## Find probability


The random variable X has the pdf: 

f(x)=0.3 for x=1,4 and f(x)=0.2 for x=2,3. 

That is, the pdf is represented in the following table.

<!-- html table generated in R 3.0.3 by xtable 1.7-3 package -->
<!-- Thu Jun 19 00:30:31 2014 -->
<TABLE border=1>
  <TR> <TD align="right"> x </TD> <TD> 1 </TD> <TD> 2 </TD> <TD> 3 </TD> <TD> 4 </TD> </TR>
  <TR> <TD align="right"> f(x) </TD> <TD> 0.3 </TD> <TD> 0.2 </TD> <TD> 0.2 </TD> <TD> 0.3 </TD> </TR>
   </TABLE>


1. Please calculate P(X>2.1)

*** .hint
Find all cases of X>2.1, then add up their probabilities.

*** .explanation
1. <span class="answer">0.5</span>

This is a discrete random variable. So you need to find the cases for X>1.5, and add up the probabilities of those cases. 

There are two possible values for X>2.1: X=3 and X=4.

Hence the probability is  f(3)+f(4)=0.2+0.3 =0.5
