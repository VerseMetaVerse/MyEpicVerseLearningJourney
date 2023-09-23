# MyCrazyVerseLearningJourney
My personal experience journal learning Verse seems unlikely to be of interest, but there may be bits here and there

It is hard to learn a new programming language in a rigorous in-depth manner and keeping this journal might help in those many moments where my eyes glaze over and watching grass grow is more interesting.

# Below this point, entries are in reverse chronological order

### STM

"Software transactional memory (STM) is a concurrency control mechanism analogous to database transactions for controlling access to shared memory in concurrent programming. Eventually, Verse will feature STM because it unlocks performance gains for large distributed simulations, among other motivations."

### Next steps after Lang Ref

I will probably update the journal daily at this point. After I feel very verse with Verse, I will be making UEFN game snippets. I am most curious to attempt a maximum size full PBR Island terrain to walk around in with some Verse procedural generation...

### Composite Types

- Class, Enum, Struct, Subclass, Interface, Constructor
  

### Container Types

- Tuple, Option, Range, Array, Map
- Option is hurting my head
- Map is standard fare but weak_map needs a better explanation on why it exists and what to use it for
- Tuples seem to work against the idea of well structured programs and they can SPLAT! Even though kind of stupid, I will probably like them

### Starting the Concurrency section

- This is rather unique for a potential mainstream language
- Sync, Race, Rush, Branch, Spawn, Task
- "race is one of the most useful and powerful expressions in the Verse arsenal. It is key to stopping other arbitrarily complex async code in a structured fashion — a form of early exit. It does this in a very clean way by keeping whatever tests are needed to determine when to stop separated from the code that is to be stopped.... Without race, you would normally need to sprinkle tests, such as polling all throughout your complex behavior. With race, you only need to add all stop conditions as sibling subexpressions to the complex behavior."
- "spawn expression should be treated like an emergency escape hatch, while branch should be used in place of spawn whenever possible."


### Welcome to not useful CompSci

- The famous and not useful Linked List
- https://dev.epicgames.com/documentation/en-us/uefn/linked-lists-in-verse
- There is a reason that linked lists are not included in Verse so why post a retro doc on how to implement your very own untested buggy version of a data structure? Strangest item I have come across so far perhaps


### Launching Verse, a major new programming language inside of UEFN

At first it seemed awkward. But at least the usual PRINT ( "HELLO WORLD") could be far more entertaining with an NPC that dances around saying Hello World!
- and https://dev.epicgames.com/documentation/en-us/uefn/debug-draw-in-verse

### Rollback of every if statement

Seems like a mental burden that could build up in a large body of code. We shall see...

### not not
"You can use not not expression as a way to check if an expression will succeed but make it so the expression never happens."
- it just seems like an awkward side effect and should be something like test(expression) but every language designer of any worth agonizes over every new keyword added so every programing language has these awkward bits that lurk in the backwaters...

### 0 is not equal to 0.0
"0 = 0.0 - This example will fail because 0 is of type int, while 0.0 is of type float, and int and float do not share a subtyping relationship."

### Learning Starting Point
I have started by slogging through each section of the official Verse Language Reference
- https://dev.epicgames.com/documentation/en-us/uefn/verse-language-reference
- Of course I am not going to memorize the Verse Reference on a single run-through but I have learned in the past that if I want a rigorous result at the end, that this is an important first step to become familiar with the entire language.
- Previously I had read through the online book - https://github.com/glinesbdev/versus

## Creator Portal Epic Support Really Sucks
- Tim Sweeney: everything you make has been fantastic
- Tim Sweeney: making me completely discouraged and wanting to give up on the project is the WORST thing you have done!
- I have hit a snag with my Creator Account where they want to know that I am actually well .. me. I don't travel or drive a car so I have lived my entire life without a Passport, Driver's License and Identity Card. I will attempt to contact Epic Support and see what sort of adventure I need to embark on to become "me"
- I felt a horrible sense of disappointment when I was informed that I was not actually a real person and i'm not looking forward to how long that might take to fix but logically I am a long way from making a useful demo of an island that illustrates Verse usage anyways.
- Still it did make me pause and reconsider the entire idea.
- First attempt at a support request is a dismal failure. They just repeated back boilerplate text without bothering to read what I said!

### Useful reference?
I assembled a reference page so I can keep track of Verse info that I come across:
- https://github.com/VerseMetaVerse/VerseInfo
- Lots of small updates - I need to switch my focus to the actual learning of Verse.  Since it starts out in life as "scripting" for UEFN, there are no large code projects that can really help with learning. So that is my first objective - make something useful that can become a large module to help people. All suggestions welcome.


### NEWBIE MISTAKE 1:
I have never used Fortnite before but since the sale of digital "skins" is paying for all the goodies that Epic is giving us, we should encourage everyone to do that so then where you pay for the skin there is a [HOLD] marker and clicking the button does nothing. So I google like crazy to figure out how my Epic Account can be on hold just for Fortnite and it is actually a common issue with Microsoft Store with XBOX users but I can't find anything. So it's not critical but I stared at it for 2 days since I was leaving it open to qualify for the Creator Program and then I thought, maybe it isn't an account problem. ANSWER: Click on yellow area and HOLD down the mouse button! (No comments on UX Design and I'm being laughed at by Fortnite players around the world)

### The Captivating Idea
The idea of "vast open worlds built by millions of creators for billions of players" has completely captured and inspired me. There is an actual profession of "Futurism" where people try to predict in rational scientific ways how things will progress and they never get it right. Every few decades our computer industry engages in large competitions for dominance of platforms. I think we are in a ramp-up phase to "The Metaverse Wars" that will play out in the next decade. I really like Sweeney's vision and I dislike Zuckerburg's and I am not sure who else will attempt a platform play, perhaps Amazon or Google.














