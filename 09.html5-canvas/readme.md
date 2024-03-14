# HTML 5 Canvas Master Guide

**HTML5 introduced the < canvas > element, which provides a way to dynamically render graphics, animations, and interactive content directly within a web page using JavaScript. The < canvas > element acts as a drawing surface that you can manipulate using JavaScript to create and modify visual elements.**

```
<canvas id="app" width="400px" height="400px"></canvas>
```
## Javascript To Control Canva Module One

```
let canvas = document.getElementById('app');
let ctx = canvas.getContext('2d');
```

### Draw the line

```
ctx.moveTo(0, 0);
ctx.lineTo(300, 300);
ctx.stroke();
```
### Draw the box

```
ctx.fillStyle = 'royalblue';
ctx.fillRect(50, 50, 200, 200);
```

### Draw the circle

```
ctx.beginPath();
ctx.arc(95, 50, 40, 0, 2 * Math.PI);
ctx.stroke();
```
### Draw the text

```
ctx.font = "30px Arial";
ctx.fillText("Hello Punit", 10, 50);

ctx.font = "30px Arial";
ctx.strokeText("Hello Punit", 10, 50);
```
