# class14

> this is my notes from readings we do in **_201 course_** in my advance coding scholarship 

Here is a list of things a learnt in this reading: 

# Read14: A

##   What google learnt in its quest to create the perfect teams

- [x] Our data-saturated age enables us to examine our work habits and office quirks with a scrutiny 
      that our cubicle-bound forebears could only dream of
- [x] No matter how researchers arranged the data, though, it was almost impossible to find patterns — 
      or any evidence that the composition of a team made any difference
- [x] Some groups that were ranked among Google’s most effective teams, for instance, were composed of 
      friends who socialized outside work. Others were made up of people who were basically strangers away from the conference room. Some groups sought strong managers. Others preferred a less hierarchical structure
- [x] The technology industry is not just one of the fastest growing parts of our economy; it is also 
      increasingly the world’s dominant commercial culture

- [x]And at the core of Silicon Valley are certain self-mythologies and dictums: Everything is different 
      now, data reigns supreme, today’s winners deserve to triumph because they are cleareyed enough to discard yesterday’s conventional wisdoms and search out the disruptive and the new.



## 2D Transforms:

-[x] 2D Rotate, transform: rotate(20deg);

-[x] 2D Scale,   transform: scale(.75);

-[x] 2D Translate,   transform: translate(-10px, 25%);

-[x] 2D Skew,   transform: skewX(5deg);
      you can put a comma after the first parameter to give value for y axis

-[x] on 3d you cant say rotateX or scaleZ
-[x] Skew is the one two-dimensional transform that cannot be transformed on a three-dimensional scale





## transitions

-[x] here is a list of properties that can be tansfered:
background-colorbackground-positionborder-colorborder-widthborder-spacingbottomclipcolorcropfont-sizefont-weightheightleftletter-spacingline-heightmarginmax-heightmax-widthmin-heightmin-widthopacityoutline-coloroutline-offsetoutline-widthpaddingrighttext-indenttext-shadowtopvertical-alignvisibilitywidthword-spacingz-index

here is an example

.box {
  background: #2db34a;
  border-radius: 6px;
  transition-property: background, border-radius;
  transition-duration: .2s, 1s;
  transition-timing-function: linear;
}
.box:hover {
  background: #ff7b29;
  border-radius: 50%;
}

now this means the 2 properties backgroud, border radius, will be changed over 0.2seconds and 1 second
respectively when the element is hovered over

## animation

-[x] The @keyframes rule must be vendor prefixed, just like all of the other transition and animation 
      properties. The vendor prefixes for the @keyframes rule look like the following:

      @-moz-keyframes@-o-keyframes@-webkit-keyframes

      here is an example

      .stage:hover .ball {
       animation-name: slide;
  animation-duration: 2s;
  animation-timing-function: ease-in-out;
  animation-delay: .5s;
  animation-iteration-count: infinite;
  animation-direction: alternate;
      }

i hope this make since the way they are



## 8 animations that will wow people

-[x] find in-out
-[x] change color
-[x] grow-shrink
-[x] rotate elements
-[x] square to circles
-[x] 3D shadow
-[x] Swing
-[x] Inset border

also i have a code to make the 404 ugliest error to be animated :D
