---
layout: post
title: "A Googly Case Against Erdos Number"
date: 2017-01-14 19:57:00
crosspost_to_medium: true
---

Last night I was explaining to my roommate the idea behind one Erdos Number, and we came up with an interesting idea.

Paul Erdős is to this day the most prolific mathematician in history, having authored and co-authored more than 1525 papers while traveling the world (what a badass). Because he believed math to be a social endevour, he encouraged and practiced collaboration, which is why mathematicians eventually used him as the starting point for a mechanism to quantify the influence any mathematician holds in the community. Seeking this end, they created Erdos Number.

[Wikipedia](https://en.wikipedia.org/wiki/Erd%C5%91s_number) explains it this way:
> To be assigned an Erdős number, someone must be a coauthor of a research paper with another person who has a finite Erdős number. Paul Erdős has an Erdős number of zero. Anybody else's Erdős number is k + 1 where k is the lowest Erdős number of any coauthor.

Thus the lower your number, the closer to Erdos and thus more influential you are as a mathematician. This makes sense as an altenrative to either merely counting the number of one's papers or to subjectively deciding which papers are more important than others. It's very elegant, and it is usually remarkably consistent with our intuition as to who the most influential mathematicians should befor the median number for a Fields Medalist is 3, for a Nobel Laureate in Economics is 4, and for A nobel Laureate in Chemistry, Medicine and Physics is 5.

It has however a flaw: over time Erdos numbers will increase as mathematicians with low numbers will die off and thus make it impossible to collaborate with them. This means there is a time bias to the algorithm behind this ranking system. 

My roomate and I were earlier talking about PageRank, and he thus remarked that maybe PageRank can be a better algorithm to serve the goal of Erdos Number. 

For those unfamiliar with PageRank, it's the algorithm that was the basis of Google. 

[Wikipedia](https://en.wikipedia.org/wiki/PageRank) quotes Google itself when it explains:
>PageRank works by counting the number and quality of links to a page to determine a rough estimate of how important the website is. The underlying assumption is that more important websites are likely to receive more links from other websites.

Therefore, one could theoretically use PageRank to set up a system where the most influential mathematician would come out to be the one whose papers are referenced the most. This way we would not only remove the time bias since years from now someone could discover something so integral to math that it comes close to previous thinkers, but it also encourages an optimized balance between productivity (for a higher number of papers will increase your chances of references) and quality (for a more influenial paper should have a higher score than 10 mediocre ones).

There we derive a mathematician's influence through the impact their papers have had on the community at large, which over time will converge towards a much more accurate number.

Furthermore, the Erdos number algorithm fails in the case of a malignant actor who bribes a mathematician with a low number or by chance someone who is not even a mathematician co-authors a paper with someone who co-authored with someone who has a low number. We don't have any examples of the former, even though it's totally possible considering how much money mathematicians can make in the stock market, and we do have a couple of examples of the latter wth Judge Richard Posner having a 4 because he co-authored with Alvin E. Roth and with sociologist Barry Wellman having a 3 because of a co-authorship with Ove Frank who co-ahtored with Frank Harary. PageRank takes care of that because their papers would most likely not contain as revolutionary of material as actual mathematicians.

EDIT: JK apparently a malignant actor problem did arise. According to Wikipedia: "In 2004 William Tozier, a mathematician with an Erdős number of 4, auctioned off a co-authorship on eBay, hence providing the buyer with an Erdős number of 5." #damn

Therefore, PageRank solves all of these problems while retaining the original implementation's elegance, which is why I contend it should be embraced as the new basis for Erdős number.
