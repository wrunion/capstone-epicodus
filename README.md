#### Winter A. Runion

#### ADHD-PT

##### Description
<!-- _A summary of what you envision the project becoming. This does not have to be detailed or even a set in stone, but rather a snapshot of your current goals_ -->

An app that creates simple, easy-to-follow exercise plans based on user input. Designed to be easy to use on the go, with minimal setup on the user's part.

For example, the user could enter that they have 15 minutes available, and want to work on at least one exercise for hand dexterity and one for leg stability, and the app would give a 15 minute mini-exercise plan that includes both of those things.

The dataset is a predefined set of exercises that were prescribed to me by my Physical Therapist.

##### Use Case
<!-- _Who are the main users? What problems are they facing that you will solve? What will it do for users? What is the purpose/goal of the project?_ -->

The primary user right now is me. I have Ehlers-Danlos Syndrome, a condition that causes hypermobility of the joints, and that can be treated effectively with physical therapy. 

The problem is that I also have ADHD, so even though I've been to a Physical Therapist and have a comprehensive list of exercises for various body systems, I inevitably forget about some or all of them. 

**This app would help me overcome a major barrier to treatement: executive dysfunction.** Starting a new exercise regiment is difficult for most people, but for me in this case, where there's a medical aspect and efficiency calculations to be done - as to which exercises I should do and how many and when - I spin my wheels and just get stuck.

A custom ADHD-PT App would solve the issue by calculating which exercises I should be doing on rotation, and displaying them to me on a timed schedule. 

Then, instead of spending time overthinking, all I have to do is press a button, get an exercise, and then do it!

##### Minimum Viable Product
<!-- _List the absolute minimum features the project requires before it is considered in a pre-alpha state_ -->
 * App displays a diagrams and instructions for various physical therapy exercises
 * Each exercise is tagged and catalogued, according to area of the body, type of functionality it targets (ie balance, strength, mobility, dexterity, endurance)
 * User can enter: the amount of time they have, the equipment they have access to (yoga ball, hand weights, resistance band, or none), and whether they can sit, lie, or stand.
 * User can optionally enter: the body areas they want to focus on, how many different exercises they want. 
 * The app will calculate which exercises best fit the criteria, and will respond with images and instruction.  

##### Tools for MVP
<!-- _List the tools, frameworks, libraries, APIs, modules, resources, languages, etc that will be used to create your MVP. Be specific._ -->
 * React 
 * Redux
 * Redux middleware, including Thunk, for async actions. 
 * _WIP: somwhere to store the instructions and diagrams of the exercises. Possibly excel? Or a simple .json file. Ask Kent._
 * Materialize UI CSS framework, to design with a "mobile first" mindset.
  <!-- * Since the dataset is pretty limited - around 20 or so exercises, each of which has a simple diagram and a short text description - I'll probably just create a single .json file and pull the data from there. I'll consider alternatives though.  -->

##### Additional Features
<!-- _If you finish developing your MVP and have time to spare, what features do you want to work on next? Be specific._ -->
_**My main stretch goal would be to create an algorhythm that makes sure I'm getting in enough of each exercise each week.**_ 

Other stretch goals may include:  
* Embedded music that plays for the same amount of time you should spend on an exercise
* "Acheivement badges" or animation type things that play once you've completed your exercises
* Timers to remind you throughout the day to do your exercises
* A back-end database that records your progress daily

##### Tools for Additional Features
<!-- _List the tools, frameworks, libraries, APIs, modules, resources, languages, etc that will be used to create your additional features. Be specific._ -->

* Each of the stretch goals I listed has a variety of possible implementation strategies.

* If I have the time to add additional features, I'll determine the best route to take at that time.

##### Additional Information
<!-- _Is there anything else you’d like your instructor to know?_ -->

My ultimate goal would be to turn it into a mobile app, probably using React Native. 

That's more than I'll be able to do in two weeks, so it's not part of this proposal, but I'll be building and planning with an eye toward converting to mobile. 

I'm open to any feedback you might have!
