---
title: "Explaining the Bloc Scoring Method & Sequential Proportional Score Voting Method"
date: "2020-04-19"
---

A week ago, the results for the 30th Senate were [posted](https://www.reddit.com/r/SimDemocracy/comments/g07h6t/results_of_the_30th_senate_election/). However, there was some controversy. Xvillan, one of the contestants for the election, claimed that the scoring method used in the election (sequential proportional score method) costed him a seat in Senate. This led to a bill to go back to the previous scoring method (bloc score method), however, it [failed in Senate](https://www.reddit.com/r/SimDemocracy/comments/g2nj4l/senate_vote_5_bills/). This post explains what the bloc score method and the sequential scoring method are.

## So, what is the Bloc Scoring Method?

The bloc scoring method is a method used to find the average scores of all candidates. In the Bloc Scoring Voting Constitutional Amendment, it says:

> **§3.** Appendix §1.5. Shall be amended to:
> 
> "**§1.5.** Voters will score whatever candidates they wish between 0–5, with 0 being the lowest and 5 being the highest. Blank responses will be counted equivalent to the square root of the average score. The candidate with the highest average score will get the first seat, with each candidate in the succeeding place getting a seat until no seats remain.”
> 
> [Bloc Score Voting Constitutional Amendment](https://docs.google.com/document/d/13cVcDyGXuymVKMir_UrEwW5_tePVnG3a2GV5UBBZCrk/)

This means that once all of the results have been tallied up, the average score will be calculated. If there's a blank response, it'll be the square root of the average score for the candidate. If there is a tie, there will be a runoff that will be held, and the winner of the runoff wins the tie. Once that's cleared all out of the way, the candidate with the highest average score gets the first seat, and the rest of the candidates getting a seat until no seats left.

SimDemocracy used to use this in Senate elections, however, it has been superseded by, you guessed it,

## The Sequential Proportional Score Voting Method

(dun dun dunnnnnn!)

Ever since this was amended into the Constitution, SimDemocracy has been using this for Senate election scoring.

This, however, is a bit more complex than the Bloc Method, so, I'll try to explain as best as I can.

> **§1.5.** Voters will give each candidate an integer score between 0 and 5, with 0 being the lowest and 5 being the highest. Blank responses will be counted as 0s. Each of these score ballots will be converted into five virtual approval ballots using the Kotze-Pereira transformation, each with an initial weight of 1. The unelected candidate with the greatest number of weighted virtual approvals is elected, and all virtual ballots are set to have weight 1/1+m where _m_ is the number of candidates approved on that ballot who were already elected. Repeat until all seats are filled or all candidates are elected.
> 
> [SimDem Constitution, Appendix 1.5](https://docs.google.com/document/d/1x3EwwglsRgnBRDhJOB8DcSZHG7ZLahG_enitXqqvDWA/edit#heading=h.jj8r0y1g96nf)

Here's a little explanation:

- Blank responses to any candidate will be counted as a 0, instead of the square root of the average score
- Score ballots will be converted into virtual approval ballots via the [Kotze-Pereria transformation](https://electowiki.org/wiki/Kotze-Pereira_transformation), each with an initial weight of 1
- Instead of the highest average score, the candidate with the greatest number of virtual approvals is elected.
- Once that's cleared out, all other virtual ballots are set to have a weight of 1 / 1 + m
- This repeats until all seats are filled or all candidates are elected

"But how does this handle ties?", you may ask. Well, dear reader,

> **§5.3.** Ties at any point in the election calculations shall be broken in favor of the candidate with the greatest unweighted score total. If there is also a tie for unweighted score totals, the tie will be broken pseudorandomly with all tied candidates given an equal probability of winning.
> 
> Article 2 of the Constitution

## Conclusion

In conclusion, this post attempts to show the difference between two Senate scoring methods - the Bloc Scoring Method, and the Sequential Proportional Score Voting Method. It is up to you to choose what method you prefer. Comment down below if you want to share your opinion on these.

Cya!
