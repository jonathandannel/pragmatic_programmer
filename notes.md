## Philosophy
### Care about your craft
### Think about your work

- Pragmatic programmers don't shirk from responsibility.
- We rejoice in accepting challenges and making our expertise well known.
- If we are responsible for a design, or a piece of code, we do a job that we can be proud of.

### The pride of ownership
> "I wrote this, and I stand behind my work"

Your signature should come to be recognized as an indicator of quality. People should see your name on a piece of code and expect it to be solid,
well-written, tested, and documented. A really professional job. Written by a professional.

## The system
### Notes to self:
- You need to always be thinking about the big picture (the system as a whole).
- You are not alone. You're working on a team of engineers to build complex systems together.
- Don't lose focus or get in the routine of doing what is merely "good enough".

### Software entropy
Don't live with broken windows!
- Bad designs, wrong decisions, poor code all contribute to software entropy
- Fix problems as soon as they’re discovered - neglect accelerates software rot
- If truly not able to fix immediately, take some action to prevent further damage

### Good design is easier to change than bad design
- The ETC principle: Good software is well designed if it is Easy To Change (ETC)
  - Ex: Single responsibility principle (ETC)
    - A change in requirements is mirrored by a change in one module (ETC)
  - Ex: Decoupled code (ETC)
    - Isolating concerns makes them much easier to change (ETC)
- The ultimate fallback when faced with uncertainty is to *make what you write replaceable*
  - Keeping code decoupled and cohesive is what you should be doing all the time
  - This approach ensures that whatever you are working on won't be a roadblock in the future

### Orthogonality
Every time you write code, you run the risk of reducing the orthogonality of your application.
Be aware of what you're doing at all times, and the potential effects on the rest of the system.

Orthogonality is closely related to DRY:
- DRY: Reducing the duplication within a system
- Reducing the interdependency among the system's components

### In practice
- Focus on designing components that are:
  - Self-contained
  - Independent
  - Have a single, well-defined purpose
- Benefits: 
  - Changes are localized to a small area. There is no need to keep changing existing components when adding new ones.
  - Promotes reuse. If components have specific responsibilities, they can be combined with other components in new ways.
  - The more loosely coupled the systems, the easier they are to reconfigure and re-engineer.
- Write shy code:
  - Modules shouldn't reveal anything unnecessary to other modules
  - Modules shouldn't rely on other modules implementations

## Debugging
> Debugging is a sensitive, emotional subject for many developers. Instead of attacking it as a puzzle to be solved, 
your may encounter denial, finger pointing, lame excuses, or just plain apathy.

### Fix the problem, not the blame
It doesn't really matter if the bug is your "fault". It is still your problem.

Before you start debugging:
- Turn off the defenses that you use to protect your ego
- Tune out any pressure that you may be under
- Don't panic!

## While coding
### Avoid programming by coincidence
Developers who don't actively think about their code are programming by coincidence. The code may work, but there is no particular reason why.

- Always be aware of what you are doing. 
- Can you explain the code, in detail, to a junior programmer? If not, you may be relying on coincidences.
- If you don't know why it works, you won't know why it fails.
- Proceed from a plan, whether it's in your head or on a whiteboard.
- Rely only on reliable things. Don't depend on assumptions.
- Don't just test your code, but test your assumptions as well. Don't guess - actually try it.
- Dont let existing code dictate future code. ALL code can be replaced if it is no longer appropriate.

## When things are difficult
Your insticts are subconsciously receiving feedback from the code, and trying to get you to listen!
### Fear of the blank page
When you feel stuck or like you just can't start, your years of experience and wisdom that you've been accumulating might be trying to speak to you. 
Find out where those doubts are coming from. Is it because deep down, you know your intended approach is incorrect? 

### Don't think outside the box, FIND the box
- Enumerate all the possible avenues you can take
- Don't dismiss anything, no matter how stupid or unusable it sounds
- Go through the list, and explain why each path cannot be taken.
  - Are you sure?
  - Can you prove it?

### Ask the important questions
- Why are you solving this problem?
- What is the benefit of solving it?
- Are the problems related to edge cases?
  - Can you eliminate them?
- Is there a simpler related problem that you can solve?

### Fighting yourself
When coding is difficult and feels like walking uphill in mud, your code is trying to tell you something:
- This is harder than it should be
- The structure or design might be wrong
- You're doing too much

### Unblock yourself playfully
> Tell yourself you need to prototype something. If you're facing a blank screen, look for some aspect of the
project that you want to explore. Maybe you're using a new framework and want to see how it does data binding. Or maybe it's a new algorithm,
and you want to explore how it works on edge cases. Or maybe you want to try a different style of user interactions.
If you're working on existing code and it's pushing back, then stash it away and prototype something similar instead.
Remind yourself that prototypes are meant to fail, and that prototypes get thrown away even if they don't fail. There is no downside to doing this.
Create a comment describing what you want to do, and start coding.

