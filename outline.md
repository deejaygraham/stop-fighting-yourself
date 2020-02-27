# Stop Fighting Yourself

## Sunderland University March 2020

- Opener
  - Thank you for being here
  - Who I am - Sage, career - motion control systems, stock control barcoding
  - Questions at any time
  - Who writes code?

- 4 hard problems in Computer Science
  - naming things
  - cache invalidation
  - off-by-one errors
  
- Actually 4th Thing 
  - Collaboration
  - Myth of lone genius
  - Truth software development is team sport
  - Too much for one person to do
  - Not healthy way to work
  - Heroism
  - Stress
  
  "If you want more effective programmers, you will discover that they should not waste their time debugging, they should not introduce
  the bugs to start with." - Edsger Dijkstra
  
- Styles of Working, in increasing levels of collaboration
  - Individual
  - Pair
  - Strong Pair
  - Swarm
  - Mobbing
  
- Really this is all about Communication and Feedback
   
- Communication
  - Why do we write code?
  - To Communicate!
  - With Yourself (CP story)
  - Always wanted to travel back in time to fight a younger version of yourself? Software development is the career for you! @Loh
  - With your future self (or an unknown team mate)
  - With computer
  - With Team mates 
  - With the customer

- Feedback
  - Goal is being paid to create value
  - Build works
  - units work
  - pieces fit together
  - whole system works
  - Feedback from the code: how have your changes affected the overall system for good or bad.
  - Feedback from the team: concrete feedback in the form of acceptance tests or scripts test overall system. How close are we to done?
  - Feedback from the customer: what to work on next, based on current state of system.
  - Compilers
  - Automated tests
  - Automated deployments
  - DevOps
  - Observability 

- Rogers AR
  - Early in my career, from 25 + 
  - Delta wrapping lots of intensive maths for movement
  - Mentor (Richard Calvin)
  - Self taught, ignorant of most development practices, not really written anything very exciting or important.
  - I invented Pair Programming and Code Reviews
  
- Hillboro Illinois
  - Working on stuff that didn't really matter
  - Middle of Illinois
  - Glass factory, hot and dirty in a tiny out building away from the main factory
  - Writing C code
  - Hot Glass
  - Super dangerous and makes a mess when things go wrong
  - Putting in new M200 system
  - Building on own machine, push out code changes
  - See what happens!
  - Long trek to go in and see if you are even more unpopular
  - Not paying close enough attention especially first thing on a morning.
  - Big piles of glass is not the best when someone else has to 
    clean up moulds 5 and 6 times a day.
  - Needed to make changes
  
- Pair programming
  - Every change was worked on by two people. Usually one person typing but two chipping in ideas 
  - Each person watching for failures, mistakes etc.
  - Continuous Code Review
  
- Code Reviews
  - I suggested going through code with someone else to get a sense of what it was doing was sensible.
  - Not all situations are like this but since then I have found it useful to apply to every other job.
  - May not be a pile of glass but if your code is valuable enough for someone to use, it's valuable enough 
    for them to be upset when it stops working. 

- How to Code Review
  - Code review - Writer
    - Walk through code (rubber duck it)
    - Run the code (does it compile), does it work?
    - Can you understand it?
    - What would cause it to change?
    - What would cause it to break?
    - Are names as good as they can be?
    - Write unit tests
      - tests code from multiple angles
      - who writes code, fiddles to get it to work (and doesn't know why)
      - scared to touch it again in case it breaks ?
      - feedback for changes, regressions, improvements
    - Easy to run tests to demonstrate behaviour.
    - What other documentation do you need?
    - You are not your code
    - SOLID is a scam
      - Single responsibility
      - Err...
      - Do one thing ...
      Pay attention to demeter
      coherence 
      coupling
      
    - Simple Design
      - Passes all tests
      - Simplest it can be
      - Uses fewest parts
      - Reveals intent.
    
  - Reviewer
    - Be tactful
    - Use Socratic method
    - Ask questions rather than statements
    - Not (Why is this so awful)
    - Consider perfection game?

  - Perfection Game
    - Would you be willing to hear some feedback?
    - How could you improve on this?
    - Here's 5 things 
    - I would score this 5 / 10 because I could improve 5 things
  
- Pairing
  - One person has an idea, takes keyboard and talks about the idea as they are typing it out. 
  Think about syntax and expressing the idea.
  - Other person thinks about next things coming up, next problem, next test ...
  - Swap over regularly
  
- Strong Pairing
  - Rubber Ducking
  - Increase quality by making your thinking explicit
  - Pair is now a transcriber
  - Swap
  - From I have an idea give me the keyboard to I have an idea, please take the keyboard

- Questions

- Closer
  - Thank you for being here
  - Available to chat
