# Week 05 - Level Design 1
Today we will be moving from our Challenge design to turning these Challenges into encounters, these encounters into our level, and creating the connective tissue between these different elements.

## Notes
### Capturing your design
A big part of these tasks is about capturing your design as you make it. Not only will you be marked on your iteration and documentation, but it is also just really good practice to have. So far, we've been asking you to make notes and capture these in your repo. However, today we are going to be actually building some of the level design artefacts proper, so it is really important you are storing them in your design document. You may wish to open that file (`DesignDocument.md` in the assignment repo) and edit it as you go.

### Take it easy
This prac is going to involve a lot of different examples of prototyping tools and forms thrown out at you. Some of this is covered in the Week 5 lecture, and more in Week 6. However, the idea here is that we want to show you the breadth of ways you can use design thinking and iterative design processes to make your levels. So, when you get to the part where we are asking you to experiment, go easy on yourself. The point isn't for you to try them all, but for you to try enough to find what works for you.

There is a lot to level design, hence why we cover it in two lectures. Don't be afraid to come back to some of these concepts next week.

## Tools used
Today's task uses (but is not limited to):

* Github Desktop (or your Github client of choice)
* Unity
* A prototyping tool of your choice. Some options:
    * Powerpoint
    * Virtual Graph Paper
    * draw.io
    * Adobe Illustrator
    * Good ol' fashioned pen and paper!

## Assignment deliverable
Today, you will begin work on the encounter design and prototyping of your level. These are elements that you must document in your report, so you should be making sure to add photos/screenshots of whatever you create today into your repo. If you are creating your prototypes physically (such as in a notebook), make sure you retain the drafts just in case. If you are using a drawing program, keep the necessary files so you can come back and edit or restore them later.

## Section 1 Encounters Design (30 min)
We are going to start our level design proper via encounter design, as discussed in this week's lecture.

When crafting your encounters, you want to think of them as <b>units of gameplay</b>. Exactly how this looks in your game will depend on what you are trying to achieve, and may even evolve between encounters. However, some questions to ask about your encounters are:
* Should this be a single screen, where the player can see all the "pieces" at once?
* Should this be a bigger section of a level, which might involve movement around space with the camera doing the same?
* Should this leverage the revealing and hiding of elements, such as having the player move between two areas a couple of times as "one encounter"?

Level design is about the movement of the player in physical space, so take a moment to think about and write down how the player moves and views space in your game. Write down:

* How does the player get from one location to the next? What is hard/easy about this movement?
* What can the player see? How big a view do they have of the world, and how does this change as they move about?

With these broad understandings of your game and its design in mind, it is time to start designing your first encounters.

You'll likely move back-and-forth between your different sections. However, we're going to start by designing some encounters for section 1, informed by the challenge design work you did last week.

### Reviewing your challenges
Go back and take a look at the challenges you made last week. Which ones resonated with you? What did you decide to base a lot of your gameplay on? Identify the elements that you need to introduce the player to (remember, this should be <b>all</b> the required features mentioned in the spec, plus any of the optional ones you are introducing).

Consider what the important mechanical elements of these features are, and the related dynamics, that you need to introduce your player to in the first section of your level. Be deliberate here - if you plan on using switches, but you're not allowing the player to shoot them, you don't need to teach them about this mechanic. Additionally, more complex dynamics that come with the further combination of elements don't all need to be showcased here, as this might overwhelm the player.

#### Storyboarding
Now, begin crafting an encounter to introduce your player to one of more of these features. In some cases, you will want to introduce a feature in total isolation (such as a moving platform). Other times, it might be necessary and more engaging to introduce two or more at once (such as the acid pit and checkpoint). There are no hard and fast rules here - refer back to the design theory presented in this week's lecture to understand how to craft these.

One of the only prescribed forms of prototypes in the assignment is storyboards for these initial encounters. So, start drafting out some storyboards for this encounter. We will be diving into this form a bit more next week, but for now simply map out a few sketches (either pen and paper, or using some basic drawing tools like those listed about) to show the sequence of events in your encounter: 
* How does the player approach these elements? What do they observe? 
* What are the broad-stroke responses they can make, and what are the consequences? E.g, the player misses the jump and hits the acid pit, so respawns and starts again.

Don't get too hung up on the spatialisation of this just yet - you want to keep those constraints we mentioned before about movement and what the player can see in mind to stop you from going off the rails, but you will be working out the details later. You can find an example of a storyboard here, depicting the sequence of using a defiblirator in the game <i>Dirty Bomb</i> (Image source: https://www.dirtybomb.com/news/the-design-of-dirty-bomb/):

![A gameplay storyboard from the game Dirty Bomb.](images/DirtyBombStoryboard.png)

Try to create two-three different encounters. You'll be coming back to this later in your design process (probably outside of class!), so let's not get too in the weeds here.

### Section 2 Encounters Design (30 min)
It's now time to repeat your encounter design process, but instead for Section 2 of your level. These encounters will be a bit different: we can assume players have completed section 1, and are now more familiar with the mechanics, so it is time to introduce some more interesting challenges for them to sink their teeth into.

The challenges you built in last week's class can really help you here. As you spent last week's class exploring different types of challenges, you will now have an idea as to what you want this to look like in your level. See which challenges from your test scenes (or other notes) can be turned into encounters. Try drafting another two-three encounters.

#### Other prototype methods
While we ask for storyboards for all of the encounters where the player is introduced to the different elements, this is the only section where we prescribe this method of prototyping.

There are many different ways to prototype at this "narrative" layer. Don't be afraid to experiment. Some ideas:
* Short paragraphs that tell the "narrative" of the encounter. Maybe put together in a tool like [Twine](https://twinery.org)
* Greyboxed encounters in a test scene that show the layout of an encounter but aren't specific about exact geometry.
* Annotated screenshots where a still of the encounter has been created, then drawn over with arrows and notes to indicate movement, etc.
* "Lego" prototypes that use blocks, toys or similar existing artefacts to map out an encounter. The image below shows an example of this (source: https://www.workshopper.com/post/design-thinking-phase-4-everything-you-need-to-know-about-prototyping)

![An image of a prototype using lego.](images/legoprototype.png)

We really encourage experimentation here and drawing on what you know. Get messy, and reflect on your findings in your design document!

## Molecule Diagram (30 min)
At this stage, you should have 4-6 different encounters. It's time to "zoom out" on your design and consider your level from a topological perspective. 

The topological view of your level is concerned with the general arrangement of the different encounters in your level, and often is done in a "molecule diagram" or other similar node based format. 

When working with a topological view of your game, the key here is being able to step back and take a look at how your player moves through (and sees) your level via the arrangement of your encounters. As such, we recommend prototyping this using something easily modifable. Nodes in Powerpoint, [Figma](https://www.figma.com/) or [draw.io](https://app.diagrams.net/) are handy. Or sticky notes if you've got a big enough wall and some thread to create links between them!

Your topological view should illustrate how a player gets from one point to another without worrying about the specifics. E.g., it should illustrate they have to move down along a winding path, but not the actual structure of that path. Here are some examples from former Ubisoft developer Iuliu-Cosmin Oniscu (source: https://iuliu-cosmin-oniscu.medium.com/molecule-design-439194cc82bf)

![An image of an example molecule diagram](images/moleculediagram1.png)

![An image of an example molecule diagram](images/moleculediagram2.png)

Remember, the player should be introduced to all the features in section 1 before being tested on them in section 2. So, while we do want some non-linearity, you really want to consider how you will get players from section 1 to section 2 (hint: how do we say to do this in the Week 4 lecture?).

## Iteration and connectivity (30 min)

By now, you've got a pretty good picture of how some of your level is going to hang together. You've identified some encounters, and in creating your molecule diagram possibly refined them or identified where you need more or less of them.

For the rest of the time, continue your design work being guided by the following provocations:

<b>Iteration</b><br>
Now that you have your design in both a micro (encounters) and macro (topology) view, is it working? What could be changed? Do the encounters need re-arranging, or are further tweaks needed here? Don't be afraid to "zoom in and out" on your design by going back and forth between modifying encounters and changing their place in the big picture.

<b>Connectivity</b><br>
So far we've focused on the encounters that are teaching and challenging the player. What about everything in between? Are there opportunities for the player to stop and look out upon the world? Can they see upcoming challenges as they travel by them on a moving platform? Are there examples of both positive and negative space throughout your design? Start thinking about these kinds of encounters and how they might fit into your level to modulate your dramatic arc.

<b>Section 3</b><br>
You might want to think a little about Section 3. Sometimes it can be a good idea to have a rough idea of the whole picture and where you want the player to end up, as this will allow you to think about how you can really teach them everything they need to know in Section 1, and properly test them in Section 2 to make Section 3 a big payoff.

## Next Week
Next week we will work on moving to the geometry of our level, mapping out exactly what the level looks like both on paper and in engine.