---
title: 'Smalltalk > Impact'
---

What were some things people were able to accomplish as a result of Smalltalk?

Wirfs-Brock summarizes Smalltalk's impact in broad terms:

> "Starting in the early 1970s the early Smalltalkers and other Xerox PARC researchers invented the concepts and mechanisms of Personal Computing, most of which are still dominant today.

(WB)

He elaborates on this:

> Using the Smalltalk platform, the fundamental concepts of a personal graphic user interface were first explored and refined. Those initial concepts were widely copied and further refined in the market resulting in the systems we still use today…Smalltalk was also the vector by which the concepts of object-oriented programming and design were introduced to a world-wide programming community. Those ideas dominated for at least 25 years.

(WB)

David Buck and Craig Latta go into some more detail about what Smalltalk introduced:

- "the first overlapping windows, bitmapped graphics system…this whole idea of windows with scrollbars being controlled by mice" (although they note that the mouse was not invented by the Smalltalk team, only popularized by them)
- Pop-up menus
- Text on computers with multiple fonts
- The scrollbar
- Agile methods, including Extreme Programming and Scrum
- Design patterns
- The Model-View-Controller pattern
- The concept of refactoring, and refactoring tooling
- Unit testing, and the xUnit family of testing frameworks
- Just-in-time compiling and runtime optimization of method implementation

![Screenshot of Smalltalk demonstrating graphical features](../assets/images/smalltalk/impact/gui.png)

Wirfs-Brock summarizes:

> Smalltalk did something more important than take over the world—it define the shape of the world!

As a result, if we say "Smalltalk has declined," that's not quite correct: many things Smalltalk introduced have persisted, and it's only the things that have *not* spread and persisted that we think of as Smalltalk distinctives that have declined.

Beyond establishing these patterns, Smalltalk enabled non-technical users to create prototypes:

> I remember meeting this gentleman who was by profession a photographer. And he showed me this prototype that they had been working on…ultimately, it was the very first spreadsheet…and it was a remarkable tour de force. And I said to him "I don't understand how you did that." I mean, I just couldn't believe this non-professional. He said "well, I'll show you"…I remember saying to him “that is the ugliest piece of code I’ve ever seen.” And he said “oh, that’s okay, because it does what I want it to do, and the professionals…are going to rewrite it all; this is the spec.” Suddenly the prototype became the spec.

(Goldberg 41:20)

The benefit of Smalltalk's tooling is also demonstrated in the creation of Squeak. It was written in Smalltalk itself--that is, in another Smalltalk version:

> Our bootstrapping strategy also depended on being able to debug the Smalltalk code for the Squeak virtual machine by running it under an existing Smalltalk implementation, and this approach was highly successful. Being able to use the powerful tools of the Smalltalk environment saved us weeks of tedious debugging with a C debugger.

(Squeak)
