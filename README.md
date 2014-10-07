#threeJs
http://www.threejs.org

Introduction to 3d development with javascript.  three.js develivers what you need.
>We are going to cover 3D Theroy, 3D Examples, 3D Game Code Walkthrough

## Theory TL;DR
3D user test results (10 secs)
*Grandma's Boy:* http://youtu.be/-ltORkYAdVk?t=1m30s

###So, What is 3D?

In the broadest definition of the term, "3D" would describe any object that occurs on a three-axis Cartesian coordinate system. If that sounds a tad technical, fear not—we'll clear it up right away.

A Cartesian coordinate system is basically a fancy way of describing the X and Y axes we're all familiar with from high-school geometry (think graph paper).

You remember making little graphs and charts with the X axis being horizontal, and the Y axis being vertical, right? Things are very much the same in the world of 3D, with one exception—there's a third axis: Z, which represents depth.

So by definition, any object that can be represented on a three-axis system is 3D. This isn't the whole story, of course.

![](http://ts1.mm.bing.net/th?&id=HN.607998396810923044&w=300&h=300&c=0&pid=1.9&rs=0&p=0)

*Read More:*  http://3d.about.com/od/3d-101-The-Basics/a/3d-Defined-What-Is-3d.htm

###2D vs 3D  Art
The process of creating 2D art is simple: grab a writing utensil, and start drawing on a canvas. You can use a pencil and paper, or you can even use chalk on a street.

Three-dimensional art is a bit more tricky. You could always create the illusion of 3D art with two-dimensional art tools, like drawing a house on a piece of paper. One of my favorite accessible examples of 3D art is using clay to create models. Whether you’re building from the ground up using putty or painting in your favorite Warhammer 40k figurine, 3D art allows you to see every angle.

![](http://ts1.mm.bing.net/th?&id=HN.607999839928060370&w=300&h=300&c=0&pid=1.9&rs=0&p=0)

*Read More:*  http://blog.smithmicro.com/2012/09/21/anime-studio/2d-vs-3d-contrasting-the-art-styles/

###Movie 3D
3D in Relation to Film/Cinema:

The basic definition of 3D space stays the same: Everything about the X, Y, and Z-axis still holds true, but there's one catch. While real world 3D objects physically exist in three dimensions, in the digital world of computer graphics 3D objects can only be represented mathematically.

3D Models: 

Any representation of an object in digital space, is called a 3D model. If you took a look at the raw information that comprises a basic 3D model, it would simply (or not so simply) be a collection of data points that mark thousands or millions of different coordinates in Cartesian space.

The word 3D means something entirely different when used in reference to 3D movies (the kind that require you to wear glasses and make you want to reach out and try to touch the things popping out of the screen). 3D films can, and often do, have an aspect of 3D computer graphics, however there are plenty of traditionally shot, non-CG films that have taken advantage of the recent resurgence of 3D cinema.

    Binocular Disparity:The key to human depth perception has everything to do with the fact that our eyes each send a slightly different image to the brain. Our brain derives a perception of distance by interpreting the difference in the image from the left and right eye. This is known as binocular disparity.

    A full discussion of how the 3D illusion is brought to life can get quite long-winded, and this isn't the appropriate forum for it. We will give you one final definition, which serves as the basis for how 3D films are created today:

    Stereoscopy: To create the illusion of depth, filmmakers have had to develop ways to mimic binocular disparity. The common means for achieving this is to use dual or alternating projection systems in conjunction with polarized glasses that ensure that the left and right eye always receive a slightly different image. This is known as stereoscopy, hence the term stereoscopic 3D.

3D means three-dimensional, i.e. something that has width, height and depth (length). Our physical environment is three-dimensional and we move around in 3D every day.

Humans are able to perceive the spatial relationship between objects just by looking at them because we have 3D perception, also known as depth perception. As we look around, the retina in each eye forms a two-dimensional image of our surroundings and our brain processes these two images into a 3D visual experience.

However it's important to note that having vision in both eyes (stereoscopic or binocular vision) is not the only way to see in 3D. People who can only see with one eye (monocular vision) can still perceive the world in 3D, and may even be unaware that they are stereo blind. They are simply missing one of the tools to see in 3D, so they rely on others without thinking about it.

Here are some of the tools humans use for depth perception:

    Stereoscopic vision: Two eyes provide slightly separate images; closer objects appear more separated than distant ones.
    Accommodation: As you focus on a close or distant object, the lenses in your eyes physically change shape, providing a clue as to how far away the object is.
    
    Parallax: As your head moves from side to side, closer objects appear to move more than distant ones.
    
    Size familiarity: If you know the approximate size of an object, you can tell approximately how far away it is based on how big it looks. Similarly, if you know that two objects are a similar size to each other but one appears larger than the other, you will assume the larger object is closer.
    
    Aerial perspective: Because light is scattered randomly by air, distant objects appear to have less contrast than nearby objects. Distant objects also appear less color-saturated and have a slight color tinge similar to the background (usually blue).

In order to represent the 3D world on a flat (2D) surface such as a display screen, it's desirable to simulate as many of these perception tools as possible. Although there is currently no way to simulate all of them at the same time, video does use a combination. For example, aerial perspective and size familiarity are automatically captured by the video camera. In CGI scenes, aerial perspective must be added so that distant objects appear less clearly (this is called distance fog).

Of course the addition of stereoscopic images (a separate image for each eye) is a significant improvement—so much so that most people think of stereoscopic films as being 3D, and all others as being 2D.
2D Film & Video

A traditional 2-D video image has width and height but technically it has no depth, i.e. everything in the image is presented at the same distance from the viewer. Still, the viewer does perceive the image as three-dimensional by subconsciously using the techniques listed above—much the same as how stereo-blind people perceive the real world.

3D video adds stereoscopic vision, meaning that two separate images are shown simultaneously—one to each eye. This presents enormous technical problems which is why there is still no perfect system almost 100 years since the first 3D movie was made.

Common display methods include:

    Anaglyphic processing (red/cyan glasses): The original 3D system, now largely out of favor.
    Polarized light system (polarized filter glasses): The most common new system for cinemas.
    Active shutter system (LCD shutter glasses): The most likely standard for the first generation of 3D televisions and other displays.


![](http://ts1.mm.bing.net/th?&id=HN.607991855582743913&w=300&h=300&c=0&pid=1.9&rs=0&p=0)
![](http://ts1.mm.bing.net/th?&id=HN.608010401252118515&w=300&h=300&c=0&pid=1.9&rs=0&p=0)

*Read More:*  http://www.mediacollege.com/3d/intro.html
*Read More:*  http://3d.about.com/od/3d-101-The-Basics/a/3d-Defined-What-Is-3d.htm

###2D vs 3D Graphics

2D Animation

    To construct a 2D animation, the animator will use bitmap images that consist of blocks of color. When these blocks of color are placed side by side, they create a picture, according to AnimationSchoolReview.com.

3D Animation

    Animation in 3D uses computer generated lines, surfaces and solids to create a three-dimensional look. The end product is an image with more perceived depth than would be obtained in 2D animation.
    
Limitations of 2D

    Unlike 3D animation, in 2D animation only one angle or side can be seen at a time, giving the image a flat look.

Limitations of 3D

    The skill sets required to do 3D animation are much more difficult to obtain than those required of 2D animation. It also tends to be more expensive to create 3D images.

The Outlook

    Both 2D and 3D techniques are now being used in the creation of animated projects. According to AnimationSchoolReview.com, this means that both 2D and 3D animations that have been artistically integrated together will become the norm on many animation projects in the future.


![](http://ts1.mm.bing.net/th?&id=HN.608030510285721449&w=300&h=300&c=0&pid=1.9&rs=0&p=0)

*Read More:* http://www.ehow.com/facts_5834100_2d-animation-vs_-3d-animation.html

###3D Categories

3-D Design, Advertising, Animation, Computer Graphics, Graphic Design, Desktop Publishing, Digital Design and Imaging, Fashion Design, Illustration, Digital Video, Interior Design and Decoration, Typography, Multimedia, Photography, Photo styling, Textile Arts, User Interface Design, Online Publishing, Game Design, Web Design, Web Application Development, and CAD Design.

> **Architecture:**

> - Combining the disciplines of art and engineering, architects plan and design the buildings we all work and live in.

> - From minimalist, highly functional buildings to structures conceived and built to inspire and awe, architects must use both their creative and technical expertise to provide solutions for the people who will use the building, the space it will occupy, the purpose the building must fulfill, and the resources available to build and maintain it.

> - The building then becomes a unique expression of the architect as artist and as engineer.

> - In addition to considerations of form and function, architects must also keep safety as well as local laws and regulations in mind.
> - ![](http://ts1.mm.bing.net/th?&id=HN.608038533286658319&w=300&h=300&c=0&pid=1.9&rs=0&p=0)

> **Computer Animation:**

> - Computer animators work in 3-D, creating their characters with the subtleties and realistic motion of everyday life. Computer animation is an artful blend of creative vision and technology.

> - Computer graphics, animation, and audio and video techniques soon follow. Your goal: Build a digital portfolio that shows how well you bring your characters and storytelling abilities to life.
> - ![](http://ts3.mm.bing.net/th?id=HN.608015263151885468&w=214&h=168&c=7&rs=1&pid=1.7)

> **Fashion Design:**

> - The Fashion Designing industry is fast-paced, competitive and rapidly changing. Hard work, determination and passion are needed to succeed in this field. Successful fashion designers must have the ability to present visually their ideas and to guide them though production.
> - ![](http://ts1.mm.bing.net/th?&id=HN.608046612126500921&w=300&h=300&c=0&pid=1.9&rs=0&p=0)

> **Graphic Design:**


> - Graphic Design programs emphasize conceptual development, strategic thinking, mastery of technique and verbal presentation in a stimulating and innovative environment. Learn to develop finely tuned skills in the areas of typography, print mediums, packaging, branding and identity, web design and motion graphics (more graphic).
> - ![](http://ts1.mm.bing.net/th?&id=HN.608020073520368717&w=300&h=300&c=0&pid=1.9&rs=0&p=0)

> **Game Design:**

> - Welcome to a world of fantasy and design at your finger tips!
> - ![](http://ts1.mm.bing.net/th?&id=HN.607997890012514568&w=300&h=300&c=0&pid=1.9&rs=0&p=0)


> **Industrial Design:**

> - Industrial designers are responsible for the designs of the every-day objects that populate our lives, combining art and engineering in their aim to strike the perfect balance between form and function.
> - ![](http://ts1.mm.bing.net/th?&id=HN.607986280712765780&w=300&h=300&c=0&pid=1.9&rs=0&p=0)

*read more:*   http://www.design-training.com/



## Development
Before we get started lets review our steps to develop with ThreeJS.  

At a thousand foot view we see a world and shapes.  The world defines our boundries and the shapes are what we are visualizing.

> world:
> - scene/camera/renderer

> shapes:
> - objects/functions

To build a world and put shapes in it.  We go through a few abstract steps.
*1* Start with a scene
*2* Add camera perspective
*3* Render canva or webgl
*4* Add objects
*5* View frame in browser

Lets start code 3D in the browser

1- ballBoxTube.htm
//DEMO WHAT IT TAKES TO SETUP UP A SCENE
//ADD THREE JS OBJECTS


2 - colorTextureShadowWebGL.htm
//ADD DONUT
//WE WILL DEMO WEBGL 
//WE WILL DEMO THE ANIMATED SPINNING DONUT IN WEBGL 

3 - avatarMove.htm
//ADD AVATAR
//ADD KEYBOARD
//WE WILL DEMO THE AVATAR ANIMATION 

4 - avatarTrees.htm
//WE WILL DEMO THE CAMERA MARKER
//ADD TREES THAT AVATAR CAN PASS THROUGH

5 - avatarTweenWalkTreeCollision.htm
//WE WILL DEMO THE TWEEN SMOOTHNESS
//ADD COLLISION DETECTION TO TREES THAT AVATAR CAN NOT PASS THROUGH



*learn more*        http://gamingJS.com
*read more:*        http://threejs.org/docs/
*online editor:*    http://threejs.org/editor/

----------------








## 3D Examples

star wars 7
http://codepen.io/silicon_hacker/pen/tuJvm

3D examples by others:

spin blocks
http://codepen.io/johnblazek/pen/DqGAg

flat design
http://codepen.io/koheishingai/pen/yfxnH

geosphere doodle
http://codepen.io/jonbrennecke/pen/yBCel

tween worm
http://codepen.io/tobbecnet/pen/Lfdxu

matrix sphere
http://codepen.io/uriuriuriu/pen/rCiqz

thermoGlobalNucularWar
http://codepen.io/naoyashiga/pen/roaBy

digiStringArt
http://codepen.io/Octavector/pen/rdbHt

texture graphic
http://codepen.io/Mombasa/pen/ivdyC

digi sponge
http://codepen.io/naoyashiga/pen/fealH

digi spin coil
http://codepen.io/code_dependant/pen/CKako

desert art
http://codepen.io/Francext/pen/xcaHD

eqlizer
http://codepen.io/caseyyee/pen/bhuFa

tween2Flat
http://codepen.io/auginator/pen/msaEH

jelly fish
http://codepen.io/zadvorsky/pen/CjlBh

## 
My results in 3D development (50 secs)
*Simpsons:*  http://youtu.be/rOgS8gTATv8?t=50s

