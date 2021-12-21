# 3D Water Droplet

![](./)

I saw this concept on twitter and decided to attempt it myself.
The Original Concept came from [Twitter](https://twitter.com/Prathkum/status/1471880296974880770/photo/2)

## My process

Essentially all i did was copy the code and boom I'm done, no biggie right? Not exactly, cause I couldn't make jack of what it all meant. I had only learnt CSS and HTML recently( like 6 month ago recent). So all i really know are the basics. I had to deconstruct the code (lol all I did was run each line of code as i wrote it to see see what it did). At first it seemed daunting. Due to my minimal knowledge of CSS i was wondering, "how the hell did he make the shape look so squiggly ?" Further "deconstruction" led me to realize that the shape is manipulated with the border radius property(duh!!). I am familiar with border radius but I was confused when I observed 8 values i thought it was just 4!.

After some research and testing I've come to learn that; when using border radius 4 values count for each corner of the square/rectangle equally. Adding a / and proceeding with 4 more values count towards one side of each 4 corners. Example the values in "border-radius: 51% 49% 48% 52%' count for the top-LEFT corner, top-RIGHT corner, bottom-RIGHT corner, and bottom-LEFT corner, respectively. Adding the '/62% 44% 56% 38%' counts for the top-left-LEFT, top-right-RIGHT, bottom-right-RIGHT and bottom-left-LEFT. So basically your manipulating both sides of a specific corner.

I was then confused about the content with the empty value. I learnt that went styling things that 'don't exist' essentially one needs to use (content: '').

It was a pretty fun little project to do.

These helped me understand the border-radius trick

- [MDN Web Docs](https://developer.mozilla.org/en-US/docs/Web/CSS/border-radius)
- [Stack Overflow](https://stackoverflow.com/questions/42879291/css-border-radius-second-radius-explanation)

## Author

- Frontend Mentor - [@shawwnscott](https://www.frontendmentor.io/profile/Shawwnscott)
- Twitter - [@\_shawnscott](https://twitter.com/_Shawnscott)
