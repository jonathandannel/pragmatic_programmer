# Philosophy
## Care about your craft
## Think about your work

- Pragmatic programmers don't shirk from responsibility.
- We rejoice in accepting challenges and making our expertise well known.
- If we are responsible for a design, or a piece of code, we do a job that we can be proud of.

### The pride of ownership
> "I wrote this, and I stand behind my work"

Your signature should come to be recognized as an indicator of quality. People should see your name on a piece of code and expect it to be solid,
well-written, tested, and documented. A really professional job. Written by a professional.

# The system 
### Notes to self:
- You need to always be thinking about the big picture (the system as a whole).
- You are not alone. You're working on a team of engineers to build complex systems together.
- Don't lose focus or get in the routine of doing what is merely "good enough".

## Software entropy
Don't live with broken windows!
- Bad designs, wrong decisions, poor code all contribute to software entropy
- Fix problems as soon as they’re discovered - neglect accelerates software rot
- If truly not able to fix immediately, take some action to prevent further damage

## Good design is easier to change than bad design
- The ETC principle: Good software is well designed if it is Easy To Change (ETC)
  - Ex: Single responsibility principle (ETC)
    - A change in requirements is mirrored by a change in one module (ETC)
  - Ex: Decoupled code (ETC)
    - Isolating concerns makes them much easier to change (ETC)
- The ultimate fallback when faced with uncertainty is to *make what you write replaceable*
  - Keeping code decoupled and cohesive is what you should be doing all the time
  - This approach ensures that whatever you are working on won't be a roadblock in the future

## Orthogonality
Every time you write code, you run the risk of reducing the orthogonality of your application.
Be aware of what you're doing at all times, and the potential effects on the rest of the system.

Orthogonality is closely related to DRY:
- DRY: Reducing the duplication within a system
- Reducing the interdependency among the system's components

### Practice
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

# Debugging
> Debugging is a sensitive, emotional subject for many developers. Instead of attacking it as a puzzle to be solved, 
your may encounter denial, finger pointing, lame excuses, or just plain apathy.

## Fix the problem, not the blame
It doesn't really matter if the bug is your "fault". It is still your problem.

Before you start debugging:
- Turn off the defenses that you use to protect your ego
- Tune out any pressure that you may be under
- Don't panic!

