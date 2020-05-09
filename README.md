# Log Book  -- Learninglearning
A log and overview of my progress as I learn web dev.

# 9/05/2020

My three main projects (LGAP, Vocabify, Squiggler) and portfolio page are all pretty much finished. I've been learning more about React and am resisting the urge to go back over the Vocabify project to refactor all the code with all of the new things I've learned. I started the project right as I was learning React and wanted to work on something that motivated me. This definitely worked but I probably ended up spending too much time tweaking it using more slightly incomplete knowledge than was necessary (as well as a patchwork of newer stuff).

In that project for example, I don't use Context (but do use React Router and render props to make a ProtectedRoute component). I also don't use Refs but do do a bit dubious DOM manipulation. I do however, use a few different lifecycle methods and use JWT authentication. I also realise that I could have used destructuring a lot more to make the code a little tidier. Other that react, there are plenty of improvements I could make serverside but again, the site works pretty well and my time is probably best spent learning new things for now rather than endless tweaking.

I'm currently learning modern React (16.8+ - Hooks etc) and  will eventually update the Vocabify code but before then, just for you dear reader, I will tidy up what I have done and hope it's good enough - it is essentially my first ReactJS app that got a bit out of control and became a bit of a labour of love. 

A slightly more rambling entry this time. It reflects my slightly meandering approach to studying and building of late. (blame to covid isolation). Time to regroup, take stock of all I've achieved and make concrete plans.



# 31/03/2020

I have read most of the first edition of YDKJS (https://github.com/getify/You-Dont-Know-JS/blob/1st-ed/README.md) which has rounded out some of my knowledge of JS although it lacks explanations of many ES6 features I have been using. I'll be sure to have look at the second edition when it is finished.

I spent a bit of time playing with the Tonejs libary. It's a library for making sound in the browser. I have a couple of mini projects on Codepen.

I've started using the debug in chrome/VSCode which is very handy.

My vocabify MERN project is mostly finished. I'll spend a bit of time in the coming days/weeks finishing up some of the projects I've got on the go so that I can move on to other things (with better code). I may come back to these early projects one day and see how much I can improve the code. 

It's been a bit of a slow month and the covid19 pandemic has thrown my plans to find a job and relocate soon into mild disarry. I'll start my jobhunt soon and in the meantime keeping improving and building.



# 21/02/2020

I've been working on four projects:
- my portfolio
- the squiggle game
- LGAP
- vocabify

I wont go into too much detail here about their content. Some notes on what I've noticed and used in some or all of the projects: I structed my scss using a variant of the 7-1 architecture which was handy - I will use it again in future larger projects. 

I used a fairly complicated webpack build (minorly tweaked boilerplate). I should spend some more time learning about it - it feels like a bit of a mess still (also, investigating npm scripts..). 

I nearly finished a pretty nice looking front-end site (LGAP). learning about meta tags, favicons etc.

I am building a MERN application which is going pretty well. I need to learn modern React (with hooks etc).

I need to learn more design patterns etc, my code is very unmodular with lots of global variables floating around which is now beginning to look really ugly and messy to me.

I'm using netlify and heroku for (free tier) hosting currently.


# 25/01/2020

I had to take some time off for various reasons. I kept reading and building but at a significantly reduced rate. In any case, I'm back at it and it has solidified the idea of this being a marathon rather than a a sprint. 

I've been focusing on front-end stuff recently as I build my portfolio and other predominantly front-end pages. I'm using npm scripts to make everything as smooth as possible.

I have a photography portfolio project for a client on the go which is exciting. html/scss/js.

I built a little karaoke webapp which uses a couple of APIs to get the lyrics and music video for a given song. React (create-react-app I think)

The new laptop (and tablet as a second monitor) is working nicely.

### What I learned:

- SCSS project architecture for an organised big(ish) site
- more fancyish CSS stuff (and some SVG)
- the value of designing before writing (and rewriting) lots of code
- some API documentation is better than others.


# 24/11/2019
THREE months into my web learning.

I have been learning and building conistently. *Again*, I have a lot of my stuff locally (and regularly using git) but haven't got into the habit of uploading to github. I'm getting a new laptop soon so all is about to change. I have basically finished The Odin Project (having skipped a couple of little things including testing) which is quite cool but I immediately started a project for a friend (and myself) so I didn't really realise. It was a milestone I hopped to reach by the end of month 3 so well done me.


## The third month:

I ended up learning moree back-end stuff this month (as well as plenty more FE) in an effort to round out my overview of the fullstack world. I am happy to say that I am now much less frequently mystified by the random articles/code  I read. Very reassuring stuff. I  also started off the month consolidating various bits of front-end knowledge but then veered off and didn't practise much as I was having fun with Express. I finished the month building a little drawing game that I am quite pleased with and plan to expand. (I managed to write a smoothing function for canvas drawing with actual maths. - finally that degree is coming in handy)

### What I learned:

- much more flexbox and grid. Some bootstrap
- lots of fun CSS stuff
- some Sass (SCSS)
- Express basics and some - (see my CRUD messageboard)
- PassportJS (local)
- MongoDB (Mongo Atlas)
- canvasAPI (see my squiggle-game)
- lots of minor improvements across the board


### Resources used:

- Misc. articles/blogs
- The Odin Project
  - to the end
- MDN tutorials (Express)
- Youtube (Academind, Layout Land)
- Documentation (e.g .Express, PassportJS, Bootstrap etc)


# 14/10/2019
TWO months into my web development learning. 

I haven't been using GitHub or Git much since learning how to use them about a month ago. I'll get my little projects uploaded here when I decide that they demonstrate ability rather than a lack thereof.. It is quite encouraging to look back on things I have made recently and realise quite how bad they are. I said encouraging.

The following recap of the first two months is from memory so it will not be exhaustive but it is probably helpful to understand my timeline to some extent (at least for me!).


## The second month:
Now I look at the list, I may have started some of these bits in the first month.

Of course, I haven't mastered JS at this point but I am now aware of the general concepts and how everything fits together. Most importantly, I can now fairly efficiently identify how to go about fixing my problems. (using docs/ref material/forums etc).

Naturally, as I now a have a better view of the landscape, I have a better view of everything I need to learn. Of course this is a good thing but at this point, I need to focus on my trajectory. I decided to put my learning of the back-end (Node, Express) on hold in favour of getting some solid front-end practice under my belt. I will set some time aside to learn Express etc. in the coming weeks but I should get also get a decent front-end portfolio for future employers to marvel at. My goal is full-stack and *I will power on*.

Happy with my progess so far. My focus on getting half decent at JS has lead to me ignore JQuery. I'll learn the basics now..

#### Possible plans for month 3: 
- Build/Upload simple flexbox/grid VanillaJS site - I should probably prove that I can use this stuff(I have some things from my first days learning - I hope they don't hurt to look at)
- Build/Upload simple React projects.(use Ant/Bootstrap/MaterialUI?)
- Deepen JS knowledge with YDKJS / Eloquent JS (*really* get my head around prototypal inheritance/promises etc)
- Learn React Routing (and more react stuff in general)
- The other thousand things I realise I don't actually know (I plan to loop back to consolidate my CSS (animations, preprocessor(SASS), flex, grid, general responsive design stuff, ...)


### What I learned:
- Plenty more Javascript concepts..
  - First look at more concepts:
   - Promises, Fetch API, Classes, Objects, Export/Import, Modules, High order array methods (map,filter, reduce..)
..etc (some better than others).
- ReactJS (decent grasp of basics but I need practice building things)
- Git 
- Github
- npm
- Webpack (not really used it)
- (started using some handy tools -Prettier,ESlint, live server)
- I used a couple of external APIs in small projects (weather, dictionary in ongoing word project)
- I used a library (ascii converter project)

### Resources used:
- The Odin Project:
  - Web Dev 101 (majority - left a few bits out)
  - Javascript (majority - left a few bits out)
  - Node (very start - no express yet.. I stopped in favour of deepening my front-end knowledge for now - mostly React)
- Youtube (mostly Mosh, NetNinja, Traversy)
- FreeCodeCamp:
  - Responsive Web Design Certification 
  - Javascript Algorithms And Data Structures Certification
  - Front End Libraries Certification (didn't do redux)
- CodeAcademy (React I&II)
- W3Schools
- javascript.info
- lots of blogs 
- - projects for advanced beginners (Robert Heaton blog)
- codewars

## The first month:
I am teaching myself and using only the finest resources available online. (That I can find. (So far) that are free). 
I started from scratch so I had to get to grips with the fundamentals. 

### What I learned:

- HTML (first look)
- CSS (first look)
- Javascript (first look)
- DOM
- (Atom text editor)

### Resources used:
- MDN docs
- Internettingishard
- W3Schools
- various blogs (more complete resource list to follow)
- CSSTricks
- Youtube (mostly Mosh, NetNinja, Traversy)
- various blogs





# 03/10/2019
I've created this repo as a place to reflect on my progress and projects as a make them. I intend to go into some detail about particular bits of the code that I found tricky or time-consuming as well as more general feelings about my progress on the whole.

