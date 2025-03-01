# 2025-02-28
Yesterday, I could not complete my tasks as I have decided for myself and I realised that I have to learn to manage my
emotions more appropriately and in case of failure - I should take my time to do double effort so that I can at least
keep up with the pace.

Today, I have started:

## Leetcode Problem of the day
These are the problems of the day given by Leetcode that I can put for today and yesterday. I have decided that I would
rather not put all my thoughts here - in this repo, rather keep the code on leetcode solution itself.

I will rather add the problems that I have solved and my learnings from it!

<details>
    <summary>2025-02-07's problem: 873. Length of Longest Fibonacci Subsequence</summary>
    
    What I learned here is that Fibonacci just requires, first start elements and the length of required sequence
    I could see that a given seq of length greater than 3 is also valid if I remove the first element, so I was trying
    to construct in opposite direction and keeping information of all possible sequences formed.

    This method is not good, rather we can also use the information that given any two endpoints as well, we can find,
    all the previous numbers that end their. So given `arr[end]` value I can uniquely lookup values in 0 to end - 1 such
    that they sum to `arr[end]` (Two Sum-II) and they can keep track of the end element inside the subproblem with
    current end such that it could be reused in future
</details>

<details>
    <summary>2025-02-08's problem: 1092. Shortest Common Supersequence</summary>

    Correctly guessed on how subsequences are matched that it would actually follow the pattern of is a subsequence
    problem, however given the constraints of problem we go out of memory.

    This is because the Maximum possible size of array approaches 10 to the power of 6, which causes a memory limit to
    be violated, instead we would have to use the total size and reconstruct it at end
</details>

## Google Leetcode Discuss Section
This section contains some of the most amazing problems as provided by Google that was discussed by the Interviewees, it
is a good place to practice various different problems that are seen in interviews.

Will be doing it by linking the discuss problem:

<details>
    <summary>[Google L4 Aug 2022](https://leetcode.com/discuss/interview-experience/2455876/Google-phone-interview-L4-Aug-2022-Reject)</summary>

    Basically solve 282. Expression Add Operators

    Didnt complete it
</details>

# 2025-02-26

This is my first log! Where I have actually set up my project and actually found all the different things that I want to
learn on my private Google Document - here is to hoping that I will be active in contributing to this everyday.
