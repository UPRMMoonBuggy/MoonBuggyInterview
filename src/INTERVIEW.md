# Interview Questions
## Before we begin:

We need to have the computers and check their portfolio's (if mentioned in resumé)

### Behavioral
1. What do you know about the Moonbuggy?
  - Should at least mention competition (shows interest)
  - **Follow up:** What is the purpose of the Telemetry department?
    - These questions can easily be answered if they looked up the team online
2. Describe the project you've worked on that you're most proud of. What did you do that worked out particularly well? [source](https://www.infoworld.com/article/2685213/application-development/3-make-or-break-interview-questions-for-developers.html)
  - This tells me a lot about what they know, what they value, what actual positions they've held on a team, and whether they actually think about what they're doing.
  - **Follow up:** Describe the project you've worked on that you're least proud of. What would you do differently?
    - I need people who can learn, and learning means making mistakes, recognizing that, and doing a better job next time.
3. How do you go about learning a new technology or framework
  - **Follow up:** Were these technologies learned because of coursework or self learning?
  - We are looking for learning dedication
4. How would you manage a project were you don't know the technologies used?
  - Testing initiative, willingness to learn and work ethic

### Technical
1. Describe what an API is and how it is useful.
  - Answer: API's (application programming interface) are useful for building software without having to implement every single piece
  - answers related to code reusability and ease of use are also acceptable
2. What is your process for finding a bug in an application? How much time do you typically spend on debugging? [source](https://www.codementor.io/blog/software-engineer-interview-questions-3ey7wme14h)
  - The first question tests the way the candidate thinks when working with difficult bugs. Every candidate has their own process, but they must use a debugging tool, understand how to sift through each line of code using that tool, and then understand what must be done to fix the bug without affecting other code within a project.
  - The second question helps gauge how often a developer needs to debug his or her own code.
3. How can we create a database?
  -  Answer: First we create a server, locally or externally, with a username and password (password is optional). Then we create the database on the server. Finally on the newly created DB we create as many tables as needed. **Note:** It's important to develop a simple sketch to know how the tables are going to work and determine how many tables are needed.
  - **Follow up:** How can we link two different tables?
    - Answer: with a primary and/or foreign key.
4. How do you find duplicate numbers in an array if it contains multiple duplicates?
  - **Solution:**
  ```
  (Pseudo code)
  set = {}
  ForEach element e in array{
    set.add(e)
  }
  return set.toArray()
  ```
  This solution works since sets don't include duplicates but arrays do.
  **Note:** Multiple answers are possible. However this is a simple question so interviewee should be able to come up with an answer if he/she has taken any programming course
  **Evaluation for this question:**
1. Did the interviewee make any questions about the input?
  - important that they do to understand the problem fully
2. Answer should be O(n) at max
  - anything more and the interviewee is clearly brute-forcing the solution
3. Answer will be verbal but shouldn't take more than 5 minutes to answer.
