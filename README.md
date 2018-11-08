# Turt2d
-------------------------


Example program (draws a blue rectangle on a light blue background):
```javascript
function init() {
  frameRate = 30; /*To make a set frame rate*/
  initFrames();
}

function draw() {
  background("lightblue");
  /*Put your main animations and code here*/
	
	penColor("blue");  
  t.rect(turt.x, turt.y, 200, 200);
	
  showFrames();
}


/*Run Code*/
animations();
```

# Functions


rect(x, y, width, height);
shape(size, shape, color(square, triangle, and circle), thiccness);
arcRight(x, y, radius, start, end);
arcLeft(x, y, radius, start, end);
star();
beginPath();
endPath();

penColor();
penWidth();

getX();    --returns turtle X coordinate
getY();    --returns turtle y coordinate
forward(distance);     --moves turtle forward (up)
backward(distance);    --moves turtle backward (down)
left(distance);        --moves turtle left
right(distance);       --moves turtle right
moveTo(x, y);          --moves turtle to specified x and y coordinates

background(color);  --sets the background of the canvas to a specified color

perlinNoise(value); --returns perlin noise function at the value


uhh... enjoy? <2

-Samuel Reams
-------------------------
