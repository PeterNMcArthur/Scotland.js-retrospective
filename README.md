# Scotland.js-retrospective
## Description
This repo has been created as a means of collating all of the talks from Scotland.js. For each talk the details of the speaker is given along with links, a summary and links to the slides/notes/videos where available.

##Thursday May 7th

### Keynote 
[Philip Roberts](http://latentflip.com/) - [@philip_roberts](https://twitter.com/@philip_roberts)

+ watch [Making Badass Developers - Kathy Sierra](https://www.youtube.com/watch?v=FKTxC9pl-WM)


### TDD in the in real world
[Dave Kennedy](http://bangline.co.uk/) - [@bangline](https://twitter.com/@bangline_)


###Chrome DevTools, Front to Back
[Katie Fenn](http://www.katiefenn.co.uk/) - [@katie_fenn](https://twitter.com/@katie_fenn)

+ Chrome dev
+ use [ng-inspector](http://ng-inspector.org/) for debugging angular code

###Look Ma No Framework
[Colin Gemmell](http://blog.pythonandchips.net/) - [@colin_gemmell](https://twitter.com/@colin_gemmell)


###Adaptive and evolvable applications
[Ben Longden](http://nocarrier.co.uk/) - [@blongden](https://twitter.com/@blongden)

####[Slides](https://speakerdeck.com/blongden/adaptive-and-evolvable-apps)


###Journey from procedural to reactive JavaScript with stops
[Gleb Bahmutov](http://glebbahmutov.com/) - [@bahmutov](https://twitter.com/@bahmutov)

+ for loops aren't as efficent as .map().ForEach()
+ Output depends only on input
+ Use event emitters instead of promises 
+ [Bacon.js](https://baconjs.github.io/) is a great tool for writing reactive functional javascript

####[Slides](http://slides.com/bahmutov/javascript-journey-scotland-js#/)

#####More information

[Original 50min talk](https://www.youtube.com/watch?v=fJSGCZhHtpc)

[The introduction to Reactive Programming you've been missing](https://gist.github.com/staltz/868e7e9bc2a7b8c1f754)

###UX of Stairs: When Simple Tasks Aren't So Simple
[Greg Tarnoff](http://tarnoff.info/) - [@gregtarnoff](https://twitter.com/@gregtarnoff)

+ Reading level of a 13 year old
+ Have transcripts for any videos
+ keyboard shortcuts are often used by screen readers, using them can interfere with user navigation

###Driving the Style Guide Driven Development
[Varya Stepanova](http://varya.me/) - [@varya_en](https://twitter.com/@varya_en)

+ websites are systems, not pages
+ designning components then use on html page
+ [SC5 style guide generator](http://styleguide.sc5.io/)

####[Video](http://sc5.io/posts/sc5n-tyyliopas-esitteilla-empirejs-ja-scotlandjs-tapahtumissa)


###The one trick to scaling your frontend codebase...
[Daniel Perez Alvarez](https://unindented.org/) - [@unindented](https://twitter.com/@unindented)

+ Works on the frontend development team at Yammer
+ they use pull requests to figure out who is working on what
+ yammer is built on [backbone.js](http://backbonejs.org/) with custom components on top
+ they use [require.js](http://requirejs.org/) to handle their components but would advise using [browserfiy](http://browserify.org/) in the future.

####[Speaker notes](https://github.com/unindented/frontend-scaling-presentation)


###Creating D3 components: a journey of pain, joy, frustration and enlightenment
[Chris Price](http://blog.scottlogic.com/cprice/) - [@100pxls](https://twitter.com/@100pxls)

+ 8 rules the team learnt while creating D3 components:
 * data join in components
 * singleton elements
 * avoid g soup [don't create containers]
 * no state in components
 * seperate concerns 
 * use rebind
 * name space your events
 * expose your own events
+ create small components

####[Slides](http://slides.com/chrisprice/creating-d3-components#/)


###Cascade, Specificity and a Single name space or: How I learned to stop worrying and tolerate CSS
[Orde Saunders](https://decadecity.net/) - [@decadecity](https://twitter.com/@decadecity)

+ Object Oriented CSS
+ Create components for elements

###A Brief History of Synthesis with the Web Audio API 
[Chris Lowis](http://blog.chrislowis.co.uk/) - [@chrislowis](https://twitter.com/@chrislowis)

####[Slides](https://historyofsynthesis.herokuapp.com/)


##Friday May 8th

###JavaScript Craftsmanship
[Francisco M.S. Ferreira](http://stackoverflow.com/users/26004/fmsf) - [@fmsf303](https://twitter.com/@fmsf303)

+ use jslint to ensure only quality code is being passed
+ replace comments with unit tests
+ Turn Knowledge in to executable code over comments 

###Memory Leak Health Check - Our Quest to Diagnose & Cure 
[Andrew Duncan](http://www.swarmonline.com/) - [@andrewmduncan](https://twitter.com/@andrewmduncan)

####[Slides](https://speakerdeck.com/andrewmduncan/memory-leak-health-check)


###A Monad is a Burrito and other Functional Myths 
[Joe Nash](http://www.jna.sh/) - [@jna_sh](https://twitter.com/@jna_sh)

+ Tools for functional programming; Elm, TureScript
+ Purity limit to component interaction
+ Facebook and pusher have moved to use functional programming

###Writing Beautiful JavaScript Tests
[Kim Joar Bekkelund](http://kimjoar.net/) - [@kimjoar](https://twitter.com/@kimjoar)

####[Slides](https://speakerdeck.com/kimjoar/writing-beautiful-javascript-tests)

+ focus on readablity of test
+ write tests with only one out come
+ lots of small tests

###Accessibility & JavaScript-based websites
Mark Connell - [@mconnell](https://twitter.com/@mconnell)

+ 5% of the world is deaf to some degree
+ 4% of the world is blind to some degree
+ 58% of people access the internet through their phone at least one a day
+ 87% of people between 16-24 year old access the internet through their phone at least one a day
+ Wai-ARIA is an html5 standard to improve website accessiblity.
+ Use eventLisner("input") to communicate with screen readers better.
+ don't alter the browser's native scroll

###Improving pattern libraries, with Polymer
[Sam Beckham](http://sam.beckham.io/) - [@samdbeckham](https://twitter.com/@samdbeckham)

+ uses web components 
+ not ready for production yet

###Exploring multi-screen web techniques
[Hubert Sablonnière](http://hsablonniere.com/) - [@hsablonniere](https://twitter.com/@hsablonniere)


###Programming building blocks (literally)
[Amy Wibowo](http://shop.bubblesort.io) - [@sailorhg](https://twitter.com/@sailorhg) 
[Matt Baker](https://www.reissbaker.net/) - [@reissbaker](https://twitter.com/reissbaker)

+ Made lego

####[Slides](https://speakerdeck.com/sailorhg/legoizer-slides)


###Fire your Sysadmin: use Docker to Build, Ship and Run Any App, Anywhere
[Philipp Reither](http://what-the.scot/) - [@philreither](https://twitter.com/@philreither)

+ [docker](http://www.docker.com/) is a container for your development enviroment

####[Slides](http://www.slideshare.net/eeeep/docker-fire-your-sysadmin-and-use-docker-to-build-ship-and-run-any-app-anywhere-scotlandjs)


###What are shaders and what can they do for me?
[Jaume Sanchez](http://www.clicktorelease.com/) - [@thespite](https://twitter.com/@thespite)

+ lad did some heavy maths really quickly using parallel processing via the GPU

####[Slides](http://www.clicktorelease.com/talks/#scotlandjs-2015)

###How I went from forklift driver to developer in 9 months
[Lewis Cowper](lewis.red) - [@lewiscowper](https://twitter.com/@lewiscowper)

+ Get involved in open source projects and everyone will hire you

###Keynote
[Lena Reinhard](http://lenareinhard.com/) - [@lrnrd](https://twitter.com/@lrnrd)

+ more women needed in tech