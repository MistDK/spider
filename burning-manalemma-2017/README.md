<span style="display: none" > [You are now in a GitHub source code view - click this link to view Read Me file as a web page]( https://rawgit.com/ladybug-tools/spider/master/burning-manalemma-2017/index.html 'View file as a web page.' ) </span>

# Burning mAnalemma 2017 Read Me


<iframe class=iframeReadMe src="https://rawgit.com/ladybug-tools/spider/master/burning-manalemma-2017/index.html" width="800" height="500" >

<img src="../images/ladybug-logo.png" >
</iframe>
_Can you be at Burning Man without going there? Of course not. So let's bring Burning Man over to your place._


<span style="display: none" >Not visible in GitHub source code view or small screens</span>

<!--
<iframe class=iframeReadMe src="r1/burning-manalemma-2017-r1.html" width="800" height="500" ></iframe>
-->

## Full Screen: [Burning mAnalemma 2017]( https://rawgit.com/ladybug-tools/spider/master/burning-manalemma-2017/index.html )


## Concept


If you are not going to Burning Man, but you still need to be there then you need the terrain, the map, the Temple Burn - and he Sun.

Actually, Burning Man is more convenient as a phone app. Let's do it.

What do we need?

### Heat from Analemmas

> Analemmas are the traditional figure eight ( or infinity symbol on its side) representation of Sun positions.

* https://en.wikipedia.org/wiki/Analemma
* [Motions of the Sun Simulator]( http://astro.unl.edu/naap/motion3/animations/sunmotions.html )
* [Imgur: How the sun looks when you take a pictures at the same place and time every week for a year]( http://imgur.com/61YTxQ2 )
	* See also more links in the comments
* [StackEchange: How does the appearance of the analemma vary with latitude?]( http://astronomy.stackexchange.com/questions/12590/how-does-the-appearance-of-the-analemma-vary-with-latitude )
* [Science Blog: Why Our Analemma Looks like a Figure 8]( http://scienceblogs.com/startswithabang/2009/08/26/why-our-analemma-looks-like-a/ )
* [Stanford Solar Center: Viewing and Understanding the Analemma]( http://solar-center.stanford.edu/art/analemma.html )
* [analemma.com]( http://www.analemma.com/pages/framespage.html ) << mostly broken
* [Figure-Eight in the Sky]( http://www.astronomycorner.net/games/analemma.html ) - inclueds C Sun position code
* [The Analemma Dilemma]( http://www.math.nus.edu.sg/aslaksen/projects/Hannalemma.pdf )
* [Analemmas on the gnomon and on the dial plate]( http://www.illustratingshadows.com/analemma.pdf )
* [analemma.space]( http://analemma.space/ )


### Doh > Burning Man

> A city in the desert. A culture of possibility. A network of dreamers and doers.

* https://burningman.org/
* https://burningman.org/culture/philosophical-center/10-principles/
* https://en.wikipedia.org/wiki/Burning_Man
* https://twitter.com/burningman?ref_src=twsrc%5Egoogle%7Ctwcamp%5Eserp%7Ctwgr%5Eauthor
* https://www.facebook.com/burningman/
* https://www.reddit.com/r/BurningMan/
* https://www.instagram.com/burningman/?hl=en

### What burns > Temple 2017

> The Temple is a place of refuge, mourning, and healing. The **Temple Burn** is a solemn ritual; a cleansing, a rite of passage, a pyre. We are honored to create and share this project with the Burning Man community and invite all to contribute.

* http://www.temple2017.org/
* https://www.facebook.com/brctemple2017/
* https://www.instagram.com/temple_2017/
* https://twitter.com/temple_2017


More in the next few days. In the mean time here's some background:


### Mission

* 3D terrain, 2D raster maps and 3D structures all visible and manipulable in in a single app
* Easy peasy, free open source entry level code
* Simple dependencies
	* Three.js for 3D
	* ShowDown for Markdown Conversion
	* Mapbox for the data tiles
* Basic code is under 900 lines / 23KB
* User interface and technical code well separated
* Carry out simple Sun-related coding exercises 



### Features

* 3D terrain in very high resolution for the entire Globe
* Support for 19 levels of zoom
* 3D building data available at zoom levels 15 and 16 ~ building placed at their correct elevation
* Many raster map overlays from Mapbox, Google, OSM etc
* Go to any location on Earth by entering a place name or address
* Accurate solar calculator ~ select date and time of Sun position ~ replay the year ~ accurate shadows
* Display a variety of Solar parameters including analemmas, solar range and solar access
* Add any geometry or animations ~ include and update parametric components
* Disassemble and reassemble models
* Real-time pan, zoom & rotate
* Access on tablets and mobile devices
* JSON-like permalink support
* Save to animated GIF files ~ with custom camera paths and event handling
* Free and open source
* Easy-peasy entry level plain-vanilla JavaScript cookbook code
* Text to voice, sounds, character animation, objects follow path
* All the things we forgot to mention.



3D terrain + 3D buildings (where available) + 2D map overlays + accurate solar calculator + Sun positioning + accurate shadows + any latitude and longitude + any zoom level + any date and time + add any geometry or animations + include and update parametric components + realtime pan, zoom & rotate + permalink support + save to animated gif files + free and open source + easy-peasy entry level plain-vanilla JavaScript cookbook code + all the things we forgot to mention.

### Vision

* Taking maps to new places

## Things you can do using the script


* Use one/two/three fingers to rotate/zoom/pan the display in 3D
	* Or left/scroll/right with your pointing device
* Click the three bars( 'hamburger menu icon' ) to slide the menu in and out
* Click the [Stats]( https://github.com/mrdoob/stats.js/ ) box in the top corner to toggle FPS / MS / MB views
* Press Control-U/Command-Option-U to view the source code
* Press Control-Shift-J/Command-Option-J to see if the JavaScript console reports any errors
* Click 'Show fps statistics' to see how many frames per second your computer is giving you




## Issues

* 2017-09-11 ~ destinations not deleting previous terrain


## To-Do

* 2017-09-03 ~ Need much better interaction between the different menus/plugins
* 2017-09-03 ~ Add more flight paths from math / build your own
* 2017-08-31 ~ Add speak the Burning Man glossary / 
* 2017-08-31 ~ Add to Glitch /CodeOpen / jsFiddle
* 2017-08-31 ~ Add to bl.ocks.org
* 2017-08-31 ~ update copyable permalink update with any moves/zooms
* 2017-08-31 ~ Get Temple to touch the ground. Add physics
* 2017-08-31 ~ Add select skybox
* 2017-08-29 ~ Add mouseover highlights
* 2017-08-29 ~ Add exploded view and sectioning
* 2017-08-29 ~ Include map type in location hash
* 2017-08-29 ~ Enable multiple tile terrains
* 2017-07-31 ~ Improve geoJSON reading capabilities
* 2017-07-25 ~ Select quality of raster tile display



## Ladybug Web Solar Calculator 

* http://www.ladybug.tools/ladybug-web/solar-calculator-ladybug-web/#readme.md



## Change Log


## 2017-09-19 ~ Theo

* More R11
* Structures are working again
* Screen capture
* Added mnu-template.html
* And many small fixes

Looks like I'm getting to the end. Making things simpler was not as simple as it seemed.

## 2017-09-11 ~ Theo

* More R11
* Geocoding
* Lights and shadows
* Height scale
* More auto-loading terrain

There are three levels of existence for each script
* Standalone - for testing
* Three.js plugin as parent - for general usage
* Child - part of some larger, undetermined kit of tools

Understand how these work is not easy, but as understanding arises it tends to simplify things


## 2017-09-10 ~ Theo

* Terrain and destinations and move working OK
	* 2017-08-31 ~ Separate terrain code from basic Three.js loader
* Progress is being made on the simplification - just very very slowly
* Trick learned today: console log may parent / content window dependent

## 2017-09-08 ~ Theo

* R11
* Moving along really well - albeit slowly
* Much more consistency between plugins
* All plugins work standalone, inside an app and inside an app container 
* Today on mnu-move.html plus continuous clean-up on prior plugins



## 2017-09-03 ~ Theo

* R10
* Playa alive w/sound o"musex 
* Howler.js + soma.fm
* News items for 31st, 1st, 2nd and 3rd

* 2017-07-31 ~ Add credits to Mapbox, Google, Mr.doob, GitHub and many others  < started
* 2017-08-29 ~ Add aircraft flying about - with onboard camera < started
* 2017-08-31 ~ Add sounds and music

## 2017-09-02 ~ Theo

* R9
* Dancing in the Street - in your menu
	* 2017-08-29 ~ Add people dancing in the street



## 2017-09-01 ~ Theo

* R8
* Planes fkying much better
* Cockpit camera
* Aircraft changes type every fize seconds
* Can create animate GIFs with flying aircraft

## 2017-00-31 ~ Theo

* R7
* Add start of credits page
* Add more tooltips
* Fixes to temple params, disassemble etc
* Make several plugins more standalone
* Add wireframe to Settings
* Add move temple vertical position
* Add BlackRock Airport Chick-en
* Create animated GIF - supports aircraft
* Default text with Daily news voice synth < part of the 'Theo in a bottle' effort
* 2017-08-27 ~ incorrect tab title < fixed?

### 2017-08-30 ~ Theo

* R6
* Overheard on the Playa
	* Text to voice menu
	* Test button
	* Speak over twenty 'Overheard on the Playa' phrases
* About Map Overlay
	* Extra button on 'Overheard on the Playa'
	* Calls special helper script
	* Provides animated/visual/aural overview of the Map overlay functionality
	* Almost as good as Windows Paperclip

* https://github.com/ladybug-tools/spider/issues/6

### 2017-08-29 ~ Theo

* Dis-assemble and re-assemble
	* Piece of cake
	* 2017-08-29 ~ Add step-by-step assembly process
* Custom animated GIF creator
	* Took longer to build

### 2017-08-28 ~ Theo

* Menu structure simplified. Still needs more work though
* Adds the Temple as a parametric component
	* Adjust overall Temple width and depth, individual timbers width and depth
* Add more destinations


### 2017-08-27 ~ Theo

* R3
* Add Geocoder
* Add Overlays 
* Many CSS fixes
* Add zoom and pan terrain
* Add background gradient toggle
* Add settings menu

* All scripts must be able to run standalone and within an iframe
	* Menus must be able to appear in both states
* Menus on the right
	* So as not to interfere with TooToo menus


Many new features. Code getting a bit messy


### 2017-08-26 ~ Theo

After a slow start yesterday, more slow progress. At least screen capture was added. We now have something to show that we now have something.

A lot more good stuff coming up. I hope to have updates / new releases every day of Burning Man.

What slowed things down today was the back end - but good progress was made.

The mission is something like this:

* Single index.html
*	 Handles opening and displaying any and all files in sub-folders and wherever
* Single main menu
	* Written in Markdown
* Multiple sub folders
	* All files accessible from main menu
* Multiple scripts
	* Content may be Markdown of HTML in an iframe
*	 Menus can be markdown or HTML in an iframe
	* Allows menus to behave like dialog boxes
* Multiple sub menus
* Scripts loaded at run time
* Multiple Read Mes
	* Every folder can have its own read me
* All hosted as static files on GitHub/Bl.ocks.org/Glitch or wherever

### 2017-08-24 ~ Theo

* First commit on spider repo
