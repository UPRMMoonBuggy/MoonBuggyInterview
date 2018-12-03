# Interview Questions
## December 2018

We need to have the computers and check their portfolio's (if mentioned in resumé)

### Behavioral
- Describe the project you've worked on that you're most proud of. What did you do that worked out particularly well? [source](https://www.infoworld.com/article/2685213/application-development/3-make-or-break-interview-questions-for-developers.html)
  - This tells me a lot about what they know, what they value, what actual positions they've held on a team, and whether they actually think about what they're doing.
  - **Follow up:** Describe the project you've worked on that you're least proud of. What would you do differently?
    - I need people who can learn, and learning means making mistakes, recognizing that, and doing a better job next time.
- How do you go about learning a new technology or framework
  - **Follow up:** Where these technologies learned because of coursework or self learning?
  - We are looking for learning dedication
- How would you manage a project were you don't know the technologies used?
  - Testing initiative, willingness to learn and work ethic

### Technical
- Describe what an API is and how it is useful.
  - Answer: API's (application programming interface) are useful for building software without having to implement every single piece
  - answers related to code reusability and ease of use are also acceptable
- What is your process for finding a bug in an application? How much time do you typically spend on debugging? [source](https://www.codementor.io/blog/software-engineer-interview-questions-3ey7wme14h)
  - The first question tests the way the candidate thinks when working with difficult bugs. Every candidate has their own process, but they must use a debugging tool, understand how to sift through each line of code using that tool, and then understand what must be done to fix the bug without affecting other code within a project.
  - The second question helps gauge how often a developer needs to debug his or her own code.
- How do you find duplicate numbers in an array if it contains multiple duplicates?
  - **Solution:**
  ```
  (Pseudo code)
  set = {}
  ForEach element e in array{
    set.add(e)
  }
  return set.toArray()
  ```
  This solution works since sets don't include duplicates but arrays do
  **Note:** Multiple answers are possible. However this is a simple question so interviewee should be able to come up with an answer if he has taken any programming course
  **Evaluation for this question:**
    - Did the interviewee make any questions about the input?
      - important that they do to understand the problem fully
    - Answer should be O(n) at max
      - anything more and the interviewee is clearly brute-forcing the solution
    - Answer will be verbal but shouldn't take more than 5 minutes to answer.
