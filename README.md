# presentation 
# SVG

## (Slide - SVG)
Hello. I want to tell about SVG.
## (Slide - SVG term)
SVG is a vector graphic format—based on XML and is used to display a variety of graphics on the Web.
Under the hood, SVG documents are simple text files that describe lines, curves, shapes, colors, and text. 
## (Slide - Euronews website screenshot)
A perfect example of using svg is the euronws site. Here, each icon and even the name of the site were created with svg.
Later I will tell you in what cases and why it is convenient to use this image format. And now explore some of the internal components of svg.
## (Slide - Coordinate systems)
The coordinate system of SVG  is a bit different from the coordinate systems of mathematics.
In a normal cartesian coordinate system, the points x and y equal zero  is at the lower left corner of the graph. If X increases, the point moves to the right in the coordinate system, and if Y increases the points move up.
In the SVG coordinate system the points x and y equal zero is the upper left corner. The y-axis is thus reversed in  comparison with  a normal coordinate system. As y increases in SVG  the points move down, not up.
Points x and y are set identical values on these two pictures. The difference in coordinate systems, I think, is visible.
## (Slide – “Basic Shapes”)
Basic Shapes.
## (Slide - Diagram of basic shapes)
SVG has some predefined shape elements that can be used by developers: Rectangle, Circle, Ellipse, Line, Polyline, Polygon and Path. 
Next I will talk about each shape in details.
## (Slide - Rectangle)
On the slide you can see an example of the code, its attributes and how it is displayed.
So The rect element draws a rectangle on the screen. It has 6 basic attributes. They indicate: the position of the top left corner, the radius of the corners and  the width / height of the rectangle.
 By the way, the style attribute allows you to set additional style information. It can be used with all shapes.
## (Slide -  Circle)
The circle element draws a circle on the screen. It takes 3 basic parameters. They define the radius and the position of the center of the circle.
 The style attribute can be ignored.
## (Slide - Ellipse )
An ellipse is a more general form of the circle element, where you can scale the x and y radius  of the circle separately. Here, in attributes, you indicate the radius  and the position of the center of the ellipse.
## (Slide - Line)
The line element takes the positions of two points as parameters and draws a straight line between them.
## (Slide - Polyline)
The polyline element is used to create any shape that consists of only straight lines (that is connected at several points). 
As an attribute you specify a list of coordinates of points.
## (Slide - Polygon)
A polygon  is composed of straight line segments connecting a list of points. For polygons, the path automatically connects the last point with the first, creating a closed shape. Here the attribute is the same as for polyline - this is a list of points
## (Slide -  Path)
A path is probably the most general shape that can be used in SVG. Using a path element, you can draw all the elements that we saw earlier and  many other things. In this case, the attribute is a list of commands and parameters used by those commands.
In this example, the indicated commands mean: a pen movement, line drawing and  connecting the last point to the first. 
## (Slide – “How can we add svg to our page?”)
How can we add svg to our page?
## (Slide - Svg insertion methods)
There are four basic methods: Img- Background-image, Object and Inline Svg.
## (Slide – Img or background-image)
I  have combined these two methods into one slide, because they are really very similar. In both cases, you need to write the path to the svg file. Here no possible to work with graphics, so such methods  are best suited for content images that do not need interaction: logos, diagrams.
## (Slide - Object)
In the object tag you also write the file path . Can be manipulated with CSS. Scripts, animation work, if they are described inside SVG. This method is suitable when you need to insert some kind of interactive elements: toys, graphics and various complex objects
## (Slide – Inline svg)
And of course the svg tag itself. In this method you already need to write the code of image.
We can use all the features of svg(change size, animate),  because we have access to all its attributes. Most often this method is used for icons, buttons, small animations, in which you can easily change the different properties of svg. If the animation is harder it is better to use the object tag, because a large svg file is bad readable.
## (Slide – “Animation”)
Animation.
## (Slide - Ways to add animation)
There are 3 ways to add animations for svg:
1. CSS animation
SVG can be animated by adding an id attribute or class to SVG tags, and then styling them in CSS using @keyframes.
2. Animation tag < animate>
< animate> is an animation tag built into SVG itself. It defines how the attributes change from start to end values during the specified animation. 
3. JavaScript-based animation and interactivity
Because SVG is just a document which consists of tags, we can use javascript to interact with individual SVG elements.
In addition to standard JavaScript, there are many JS libraries for animating and interacting with SVG: Vivus.js, Snap.svg and Velocity.js.
So Css is used for simpler animation. Javascript animations offer more features. As to animations in SMIL format using < animate> tags are not recommended for use and are likely to be removed from browsers in the future.
## (Slide – Svg advantages)
Why should we use svg? Let's analyze the benefits.
## (Slide - Scalability)
Scalability – Vector images are resolution-independent and can enlarge any part of the SVG image without loss of quality. Browsers just recalculate the math next to the image to avoid  resolutions. 
When the images are small, the difference is not visible.
## (Slide – Pictures SVG/ Png)
But if you enlarge the pictures, the difference is obvious.
## (Slide - Interactivity  and  Programmability)
Interactivity  – virtually any kind of animation can be added via styling and scripting.
As regards Programmability – change SVG easily, you can use any text editor.
You can also use popular vector graphics editing software such as Adobe Illustrator, Corel Draw, and Sketch.
On the left  the SVG is opened in Sketch. On the right is the same file that is opened in a text editor, it shows the code contained in the image file.
## (Slide - Compact file-size )
As SVGs are scalable, they can be saved at a minimal file size.
Moreover, you can make your SVG files even smaller by compressing them with special utility gzip. 
## (Slide - SEO friendly )
SEO friendly – SVG images are defined in XML text files, so key words and descriptions can be used and more easily recognized by search engines. 
## (Slide - Cross-browser compatibility)
Also a plus is that  SVG is officially supported by all major web browsers, including Internet Explorer 9 and later versions.
## (Slide – Svg disadvantages)
In spite of all the positive aspects, there are some disadvantages to using svg - these are:
1. No support for older browsers such as Explorer 8 and below.
2. the file size grows very quickly if the. Svg object consists of a large number of small parts.
3. No support for three-dimensional graphics, so the photos in svg do not work.
In summary, I want to say that despite all the negative points of the format, its advantages still exceed. Svg elements are easier to manage, will make your website load faster and you won’t need to update them every time when a new resolution display comes onto the market. 
## (Slide – “Thanks for watching”)
Thanks for watching.


