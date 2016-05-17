2016-05-17

Discussion of hosting and aging infrastructure of site: <http://it.ucsb.edu/>

#### Brian reports on Drupal Con
	- Drupal now supporting big pipe, async rendering, performance improvements.
	- Education summit: Brian has been working with UC level drupal cooperation.
	Proposing an Education module fund which found some interest from Acquia.  Fund would support development as needed on modules specified for Educational institutions.  Also spoke to Drupal Assoc. about this project.
	- Conversations with UCSF about HIPA/FERPA information submitted via forms in Drupal

	- Brian working on a Drupal 8 lab distribution.

	- Drupal Module: [Paragraphs](https://www.drupal.org/project/paragraphs)
	

### Kevin Wu: [Intro to React JS](http://slides.com/kevinwu-ucsb/webserver-browser-relationship/#/)
-	Redux is used with React
-	React is not a framework.  Think of it as a library.

-	Demo with code review of a basic React application running in the browser.

-	Possible system for modernizing legacy apps
	
-	React is the 'view' in MVC
-	Redux is the state container
-	React has JSX - pseudo HTML
-	React uses 'components'
- 	WebPack transpiles ES6 to ES5 with babel because the browser (chrome) can understand this.

-	replace MVC with: FLUX Action -> Dispatcher -> Store -> View
-	YouTube: 
	Hacker Way: [Rethinking web app development at facebook
	Explaining Flux](https://youtu.be/nYkdrAPrdcw?t=622)
	Redux is an implementation of the the Flux design pattern


-	[Lynda.com Learn React](http://www.lynda.com/React-js-tutorials/Learn-React-js-Basics/379264-2.html)

- [Redux DevTools Chrome Extension](https://chrome.google.com/webstore/detail/redux-devtools/lmhkpmbekcpmknklioeibfkpmmfibljd?hl/en&usg=AFQjCNFg4ldS78uapjCGBaNjL9NvIwZGhg)


	Kevin Wu uses Atom text editor on his Mac with iTerm


----

- Brian: UC Developers Slack channel
     Do we want a Slack Channel for WTX?

	Brian: Pattern Lab - common language for designers, marketers and developers for web site building.
	http://patternlab.io


----
Kevin Wu wrote: 
    Here are some links from my react + redux talk today:

Preamble Slidedeck
http://slides.com/kevinwu-ucsb/webserver-browser-relationship#/

Greetings Source
https://github.com/ginxwar/greetings-react-redux

Greetings Live App
http://ginxwar.github.io/greetings-react-redux/

We also talked about how bootstrap works with react.  It so happens that folks are working on this problem right now:  
https://react-bootstrap.github.io/

Sources
https://facebook.github.io/react/
https://facebook.github.io/flux/docs/overview.html (precursor to redux)
http://redux.js.org (redux)

Redux is a portmanteau combining "reducer" + "flux" architecture pattern.  At its core redux is billed as a state container for your JavaScript application.  How it does this is through the "reducer composition pattern" described here http://redux.js.org/docs/basics/Reducers.html

Tons of example of shared on the Redux site, with a real world application showing how asynchronous calls are defined in your redux architecture.  Redux is a super small library that one could argue that it's more of a design pattern than a library or framework.