# JSConf '18 Notes

## Track A: Learning through Art: An Introduction to VR with Billy Roh

Take inspiration from art specifically the [obliteration room](https://play.qagoma.qld.gov.au/looknowseeforever/works/obliteration_room/)

Poly [poly.google.com](poly.google.com)

a-frame has a asset management system
create id for each item

A-Frame
- Mozilla framework
- uses semantic syntax
- <a-entity> is a generic container
- can create games

Lighting
- Spotlight
- Directional (like the sun)
- Hemisphere (ambient)

Can set decay from sorce, distance, etc

Using a single light will turn off other lights
- Be intentional
- each light incurs performance cost
- 12 light sources -> 20 fps
- 3 light sources -> 30fps

Create stickers to add to scene

Physics engine
A frame provides engine to 
- Bodies
  - Dynamic body can move
  - static body will be stick

Collision event listeners
- can turn them into a static body after it is collide with object

Each of the stickers land ackwardly because the physics engine assumes its a box
- for optimization it's a box

Moving forward
- can create paintings
- can download and remix too
- with vr can be meaingful interactive

Demo

http://billyroh.com/obliteration

## Track A: CivicHacking.JS: Helping your Community using JavaScript with Caroline Dikibo

Hackathons are great but don't provide usefulness
- Apps should be opensource cities have same problems

Learned react through mentorship

Problems with Civic hacking
- Getting access to goverment officials to build apps is difficult
- Gov't officials are hard to get a hold of

CivicHacking
- Doesn't pay
- Seeked grants for options
- Grant money as option
- Grant money takes a lot of time

Resources
- Users might only have phones
- Must consider audience some 

How to start
- Join a local brigade
- Convince your workplace


# Track A: I See: Overcoming Challenges in Software Development by Kevin o'neil

@__kev__oneill on twitter

- born with nystagmus
- born with myopia or nearsightness
- vision condition which makes eyes with uncontrolled movements
- eye will move to random directions
- amblyopia 
  - lazy eye

digital divide with people with disabilities
- pew research; disabled 3 times more likely not to go online

difficulty with getting a job
- took a year
- couldn't get to work because can't drive in california
- had to look for places with public transportation

pixel perfect
- chrome extensions can set an image and lay on top of your website
- compare final website to design
- zoom tool in macbook to help with compare with pixel perfect extensions

Themes
- Created a "City Lights UI" theme in Atom
- not created in vscode yet

Work issues with others
- because of near-sightedness
- would require others to change their settings
- there is a better way!
- vs live share / teletype

Resources
- Udacity has a great course on accessibility
- created by google
- couple chapters or couple of hours


# Track B: No time for type by Nick Nisi

Learned perl - dynamic language
- run it without much setup
- enjoyed flexibility

Javascript glue language
- not a real language when it started
- Javascript would be used for e.g. portlets, etc.

"Always bet on javascript" - branden eich
- Language of the web 

Web assembly
- not replacing javascript

Js project characteristics
- larger
- more people

risk mitigation
- frameworks fill in the gaps
- jquery: manipulation of dom
- angular: module loading

Typescript
- layer to add give us statically type advantages
- strict superset of the language
- extending it with types on top of it: e.g. coffeescript

best part of typescript
- don't need to switch to typescript
- can use //@ts-check to check typescript
- add a jsconfig.json file to project
- can annotate types in parameters
- otherwise, infer the default type
- increment slowly and allow ts and js to coexist
  - reduces barrier to conversion

interfaces
- can enforce types passed in
- normally they are in documentation but can be enforced
  
Subvert type system
- can create aliases; can use any type
- can slowly replace that interface

# Track B: I like my tests, i like i like my friends, flake-free and reliable with Amir Rustamzadeh


end to end testing
camping trips - friends tend to be unreliable
end to end testing can be reliable if done properly

renaissance of the web
- complexity has moved to front end now
- sending large javascript applicatiosn down the wire
- testing them end to end has not changed since
- 2006 (selenium) 

jsdom or dom emulation
- jsdom not a real browser
- primary way to use e2e testing

don't let users be first e2e test
- cost time and money
- otherwise, use a crash reporter
- should test exact experience of user

Cypress.io
- easy way to test to test cypress
- electron application
- can be launched with npx (it is a binary)
- can have access to devtools after launch
- can inspect requests
- easy to debug

cypress commands
- headless `cypress run --record` video recording with test run
- cypress open 

# Track A: npm and the future of JavaScript with Laurie Voss

npm audit
- tool to fix issues

need to switch from yarn
- security
- npm just as fast as yarn now

npm.community - where can track fixes
don't use github - moved to discorse

npm users aren't always writing javascript
- some use php, java, c++, c#

devs pick javascript
- pick because of npm
- more tools to get

security is a concern
- switch with TLA
- enterprise can controll what makes it into your domain

growth in context
- registry grown 1400% since 2014
- registry growing so fast new users showing up
- 51% users using less than 2 years

framework never die
- they only fade away
- start new frameworks and retire software slowly
- framework has long slow decay

react
- running away with the web (60%)
- no longer runaway growth

angular
- 40% users using angular
- download data says half users 
- angryler - angular seeing fewer downloads

ember
- bounceback
- not seen at different

vue
- guess that new users are adopting vue over react
- new users not using react

react ecosystem
- has many parts
- triump of react is because of the react-router
- was able to decouple the router from framework
- react is a trumph of modular design
- able to adapt to more use cases

Redux
- flux users abandoned to redux
- flux was highly unpopular

graphql
- red hot
- apollo is running away right now

backend frameworks
- only express

next.js
- don't need to make pita to create react app
- growth is strong

tooling
- should figure out what part to bake in

typescript
- 46% use
- don't use a seperate package manager
- microsoft used to npm
- very new microsoft of them

linters
- eslint is more popular
- security incident by eslint
- team of volunteer
- didn't turn on 2FA authentication
- password was stolen
- had a eslint credential harvester

npm security resolved this
- reset npm security tokens
- created an advisory
- 10 million users noticed in 30 minutes

npm is now enforced
- use npm fix
- use 2FA (now required)

testing developers
- more experience means take security more seriously

best practices come with experience
- more experience with more time doing this

## Future of javascript

learning from history
- nothing will last forever
- frameworks will die off
- e.g. jquery
- don't cling too tightly to your tools

it should be unwise to bet against react (next couple years)
- having more modules 
- there are so many react apps to allow it for react to live forever

what to learn
- learn graphql
- tooling getting better
- building serverside apis
- look into graphql

WASM
- web assembly
- allow to write any language and transpile to browser
- interesting idea allows great performance
- wasm-pack allows to write in rust and publish into javascript

npm is for the web
- npm is here for the web
- doesn't matter what packages; will be a registry full of other languages

web will remain under construction
- always half broken

# Track B: What's in your JS? with Ravi Lachhman

transaction handling delegated to database

javaland threads
- threads
- thread pool
- incoming requests get pool gets larger

in javascript it's equivalent is promises
- succeed or fail a single time

CNFCF jaeger 
- uber
- built in java initially
- limiting factor unable to get trace information from application
- can implment into your node client when interacting with traps
- hope to get user data was tremendous

dependency hell
- might load differently on different machines
- transitive dependency hard to debug

practice npm hygiene

profiling is important now
- figure out what is being used where

OWASP has dependency checker
CVE - common vulnerability 
- score and metric how many users impacted for vunerabilities
- getting github may let you know


# Track A: JS, Concurrency in the dom

browsers have single thread
- the main thread
- javascript runs on main thread by default
- browser cannot do anything else at the same time
- must achieve 60FPS

60FPS
- standard for being performant
- human can recognize differences in framerate
- movies run at 20fps

break into 8/16 ms
- what happens in 8ms?
- click event then need to process this event
use process
- event process
- determine new state
- do state change processing

issue DOM updates
- what happens when we don't push it out and becomes 10ms

what does this mean to end user?
- means past frame budget
- this is called jank

mobile devices
- performance isn't equal on every device

brand new device by price segments
- 15/75 percentile
- A series processes perform past moores law
- creates a different problem
- devices are not close to reality

this performance gap hurts userrs

multicore performances over time
- nokia 2 is a popular phone for 80 bucks and selling well

impact?
Ares6 test 
- does babel transpilation
- bad test
- but should introduce runtime capabilities
- entirely single-core focused

Ares6 Test output
- iphonex 23.35 seconds
- nokia 2 438.67ms

new api web workers
- 2009
- in every browser you care about
- a way to write multi-threaded javascript
- share no state
- no access to the dom

myths
- dangerous

Cloony
- await response and spawns new webwork

new ES 
- jsblucks umlot over o
- block defining here can run in any thread
- up to browser runtime to allow to run
- introduces new problem
  - issue with lexical scope
  - proposal introduces 
  
stockroom
- use redux in seperate thread

WorkerDOM
- expose dom api to webworker

original requirements
- can make react work with webworker
- support whole variety of programming
- works with some issues

use cases
- framework authors improve existing app
- run with webworker to improve performance

worker dom changes
- changes 18ms but things on main thread is reduced and improve performance
- now can break barrier of 60 ms

how does this work?

main thread / worker thread
- first thing happens runtime will create worker and load javascript worker
- worker dom works in main thread

need way to transmit between threads so minimize class types
- div can be represented as NodeType.ELEMENT_NODE
- once it's been transferred small info needed after the second time
- create hydratedNode type to transfer between nodes

what we learned 
- given same complexity of webworkers

Process to move between threads
- use sub cypher to node name
- use static keys to convert object structure to keys and index of strings
- create string pool for all parts that hasn't been recieved on both sides of threads
- represent it in succint way
- able to use integer representation of dom
- for now is very efficient

mutation
- must be able to respond to input events

mutationObserver
- can create own mutationObserver
- we can observe things like value changes



