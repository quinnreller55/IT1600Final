<!DOCTYPE html>
<html>
    
<body>
    <header>
        <h1>How to create an SVG Image</h1>
    </header>
    <main>
        <p>
            Creating a simple SVG image is relatively simple. There are many predefined shapes that you can call. Some of these include the rectangle, circle, ellipse, line, polyline, polygon, and path. To start off, lets create a simple circle.
        </p>
        <p>
            Begin by calling the SVG with "svg" enclosed with "<>". then set width and height (in pixels) to set how large the image is. It should look something like this: (remove periods in actual code) <.svg. width="100" height="100"> This will create an image that is bound by 100 pixels in width and 100 pixels in height. Next use the circle command to create the actual circle. The circle command has a couple of attributes to it: cx and cy define the coordinates of where the circle is going to be created and r defines the radius of the circle. In addition we have stroke: which defines the outline of the shape, stroke-width: how big the stroke is, and fill: which fills the shape with a color. Here is the practice code: (again without the periods) <.circle. cx="50" cy="50" r="40" stroke="red" stroke-width="5" fill="yellow">. With this you can create a simple circle. Here is an example of one of mine after adding a couple of other commands.
        </p>
        <p>
            <svg height="200" width="200">
            <circle cx="100" cy="100" r="90" stroke="black" stroke-width="5" fill="yellow"/>
            <circle cx="100" cy="120" r="40" fill="black"/>
            <rect x="60" y="40" width="80" height="80" fill="yellow"/>
            <circle cx="65" cy="55" r="17" fill="black" />
            <circle cx="135" cy="55" r="17" fill="black" />
</svg>
        </p>
        <p>
            (816)645-0305
        </p>
    </main>
    <section>
        <li>  
            <a href="README.md">Home</a>
        </li>
    </section>
</body>
</html>