# MyCrazyVerseLearningJourney
My personal experience journal learning Verse could be of interest, it contains a lot more useful references than I thought it would at first

It is hard to learn a new programming language in a rigorous in-depth manner and keeping this journal might help in those many moments where my eyes glaze over and watching grass grow is more interesting.

## First conclusion:
- after reading the Verse Language Reference - This is NOT a "scripting" language. It is a full featured maximalist big tent aim for the stars fully compiled full programming language.

## Second Conclusion: 
- Learning stuff is difficult enough so why does Epic have to screw up my enthusiasm by making a mess out of my Creator Portal application?

## Below this point, entries are in chronological order
(Previously reverse chron but that proved confusing for people)

-------------------------

### The Captivating Idea
The idea of "vast open worlds built by millions of creators for billions of players" has completely captured and inspired me. There is an actual profession of "Futurism" where people try to predict in rational scientific ways how things will progress and they never get it right. Every few decades our computer industry engages in large competitions for dominance of platforms. I think we are in a ramp-up phase to "The Metaverse Wars" that will play out in the next decade. I really like Sweeney's vision and I dislike Zuckerburg's and I am not sure who else will attempt a platform play, perhaps Amazon or Google.


### NEWBIE MISTAKE 1:
I have never used Fortnite before but since the sale of digital "skins" is paying for all the goodies that Epic is giving us, we should encourage everyone to do that so then where you pay for the skin there is a [HOLD] marker and clicking the button does nothing. So I google like crazy to figure out how my Epic Account can be on hold just for Fortnite and it is actually a common issue with Microsoft Store with XBOX users but I can't find anything. So it's not critical but I stared at it for 2 days since I was leaving it open to qualify for the Creator Program and then I thought, maybe it isn't an account problem. ANSWER: Click on yellow area and HOLD down the mouse button! (No comments on UX Design and I'm being laughed at by Fortnite players around the world)


### Useful reference?
I assembled a reference page so I can keep track of Verse info that I come across:
- https://github.com/VerseMetaVerse/VerseInfo
- Lots of small updates - I need to switch my focus to the actual learning of Verse.  Since it starts out in life as "scripting" for UEFN, there are no large code projects that can really help with learning. So that is my first objective - make something useful that can become a large module to help people. All suggestions welcome.


## Creator Portal Epic Support Really Sucks

- Every time I try to submit the application again, my Gmail SPAM folder gets "BACGROUND CHECK" SPAM so something is leaking the Epic check - NOT GOOD!
- Tim Sweeney: everything you make has been fantastic
- Tim Sweeney: making me completely discouraged and wanting to give up on the project is the WORST thing you have done!
- I have hit a snag with my Creator Account where they want to know that I am actually well .. me. I don't travel or drive a car so I have lived my entire life without a Passport, Driver's License and Identity Card. I will attempt to contact Epic Support and see what sort of adventure I need to embark on to become "me"
- I felt a horrible sense of disappointment when I was informed that I was not actually a real person and i'm not looking forward to how long that might take to fix but logically I am a long way from making a useful demo of an island that illustrates Verse usage anyways.
- Still it did make me pause and reconsider the entire idea.
- First attempt at a support request is a dismal failure. They just repeated back boilerplate text without bothering to read what I said!


### Learning Starting Point
I have started by slogging through each section of the official Verse Language Reference
- https://dev.epicgames.com/documentation/en-us/uefn/verse-language-reference
- Of course I am not going to memorize the Verse Reference on a single run-through but I have learned in the past that if I want a rigorous result at the end, that this is an important first step to become familiar with the entire language.
- Previously I had read through the online book - https://github.com/glinesbdev/versus


### not not
"You can use not not expression as a way to check if an expression will succeed but make it so the expression never happens."
- it just seems like an awkward side effect and should be something like test(expression) but every language designer of any worth agonizes over every new keyword added so every programing language has these awkward bits that lurk in the backwaters...

### 0 is not equal to 0.0
"0 = 0.0 - This example will fail because 0 is of type int, while 0.0 is of type float, and int and float do not share a subtyping relationship."


### Rollback of every if statement

Seems like a mental burden that could build up in a large body of code. We shall see...



### Launching Verse, a major new programming language inside of UEFN

At first it seemed awkward. But at least the usual PRINT ( "HELLO WORLD") could be far more entertaining with an NPC that dances around saying Hello World!
- and https://dev.epicgames.com/documentation/en-us/uefn/debug-draw-in-verse

### Welcome to not useful CompSci

- The famous and not useful Linked List
- https://dev.epicgames.com/documentation/en-us/uefn/linked-lists-in-verse
- There is a reason that linked lists are not included in Verse so why post a retro doc on how to implement your very own untested buggy version of a data structure? Strangest item I have come across so far perhaps

### Starting the Concurrency section

- This is rather unique for a potential mainstream language
- Sync, Race, Rush, Branch, Spawn, Task
- "race is one of the most useful and powerful expressions in the Verse arsenal. It is key to stopping other arbitrarily complex async code in a structured fashion — a form of early exit. It does this in a very clean way by keeping whatever tests are needed to determine when to stop separated from the code that is to be stopped.... Without race, you would normally need to sprinkle tests, such as polling all throughout your complex behavior. With race, you only need to add all stop conditions as sibling subexpressions to the complex behavior."
- "spawn expression should be treated like an emergency escape hatch, while branch should be used in place of spawn whenever possible."
- https://dev.epicgames.com/documentation/en-us/uefn/concurrency-in-verse

### Container Types

- Tuple, Option, Range, Array, Map
- Option is hurting my head
- Map is standard fare but weak_map needs a better explanation on why it exists and what to use it for
- Tuples seem to work against the idea of well structured programs and they can SPLAT! Even though kind of stupid, I will probably like them
- https://dev.epicgames.com/documentation/en-us/uefn/container-types-in-verse

### Composite Types

- Class, Enum, Struct, Subclass, Interface, Constructor
- Class *Unique* is obscure, the rest of Class would not seem surprising to a C# programmer?
- Multiple Inheritance is simulated via Interfaces just like C#
- Subclass, Interface and Constructor are all part of the Class system and nothing stands out as odd there
- Struct is just a struct - refreshing that
- Enum seems more like a primitive type and just doesn't seem to belong in this category
- https://dev.epicgames.com/documentation/en-us/uefn/composite-types-in-verse


### Working with Verse Types


- Finished studying "Type Casting and Conversion" - https://dev.epicgames.com/documentation/en-us/uefn/type-casting-and-conversion-in-verse
- It refers to [Finding Actors with a Gameplay Tag](https://dev.epicgames.com/documentation/en-us/uefn/gameplay-tags-in-verse#findingactorswithagameplaytag) which is common in the Language Reference where everything feels very incomplete and there as a ton of unique useful information in the [Verse Glosssary](https://dev.epicgames.com/documentation/en-us/uefn/verse-glossary#simulationupdate) as well
- [Type Aliasing](https://dev.epicgames.com/documentation/en-us/uefn/type-aliasing-in-verse) and [Type Macro](https://dev.epicgames.com/documentation/en-us/uefn/type-macro-in-verse) work together and there is a special identifier which is just a single underscore "_" which means "name_that_is_never_used"
- [Parametric Types](https://dev.epicgames.com/documentation/en-us/uefn/parametric-types-in-verse) and then I can escape this horrible watching grass grow section
- Parametric Types will take a few run-throughs over time:
```
Map(F(:t) : u, X : []t) : []u =
    for (Y : X):
        F(Y)
```
- Covariance and Contravariance seems to make sense at first and then veers off into alien abduction zone...
- The first section that I am considering "study first run complete" without much certainty but I can't take any more of this one right now
- https://dev.epicgames.com/documentation/en-us/uefn/working-with-verse-types-in-verse

### Modules and Paths


- Last section in the Verse Language Reference
- That's it! My first run thru of the Verse Language Reference is done!
- All directories and sub directories in your Verse project are automatically Modules that are imported with a Using statement
- A bit Deus Ex Machina there...
- https://dev.epicgames.com/documentation/en-us/uefn/modules-and-paths-in-verse

### Simulation and Simulation Update

- simulation: A simulation is the representation of the behavior or characteristics of one system through the use of another system. In Verse, this would be a computer program that runs over time. This term is broader than the term game, which is one type of simulation. In addition to games, simulations include such things as interactive experiences, art, medical visualization, architectural visualization, AI, driving/flying/military simulators, and so on. Simulations can be used on different mediums, such as virtual reality (VR) and augmented reality (AR).
- simulation update: A recurring round, step or increment of logic, behavior and other calculations for a simulation. It is often shortened to update or used synonymously with tick or frame. A simulation update generally has an elapsed time that can be constant or varied. This is often referred to as delta time, which may or may not coincide with the actual passage of time. For example, a simulation update can be faster, the same as, or slower than real time.
- A simulation update often tends to be in 1:1 step with rendering a frame — this is the default for Verse. However, a simulation update may be less or more frequent than a frame, such as when an online game client goes out of sync with the server or the physics systems while doing several iterations of the changes of a simulated object. It is also possible that a simulation would not be visually rendered at all.

### STM

"Software transactional memory (STM) is a concurrency control mechanism analogous to database transactions for controlling access to shared memory in concurrent programming. Eventually, Verse will feature STM because it unlocks performance gains for large distributed simulations, among other motivations."

### Verse API Reference


- Survey of the API is done
- It is a giant API into a giant support library
- https://dev.epicgames.com/documentation/en-us/uefn/verse-api

The THREE:

- [Verse](https://dev.epicgames.com/documentation/en-us/uefn/verse-api/versedotorg)
    - Events, concurrency, basic library such as math, and Session runtime environment as Simulation Module
- [Unreal](https://dev.epicgames.com/documentation/en-us/uefn/verse-api/unrealenginedotcom)
    - Spatial Math, Debugging draws and Logging
- [Fortnite](https://dev.epicgames.com/documentation/en-us/uefn/verse-api/fortnitedotcom)
    - Devices is huge, Characters, AI, Teams, UI, Vehicles, Playspaces and Game
 


### Next steps after Verse Language Reference and Verse API Reference

- and here I am
- Next up: Run various UEFN demos and samples and figure out how to construct Verse code within that singular runtime framework.
- (After I feel very verse with Verse, I will be making UEFN game snippets.) That won't work. The only way to feel verse with Verse is to start running and editing demos withing the UEFN environment. There is no stand alone compiler. Rigorous study will need to be very iterative...
- I am most curious to attempt a maximum size full PBR Island terrain to walk around in with some Verse procedural generation...
    - https://dev.epicgames.com/documentation/en-us/uefn/environments-and-landscapes-in-unreal-editor-for-fortnite
























