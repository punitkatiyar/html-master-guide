# HTML 5 Canvas Master Guide

**HTML5 introduced the < canvas > element, which provides a way to dynamically render graphics, animations, and interactive content directly within a web page using JavaScript. The < canvas > element acts as a drawing surface that you can manipulate using JavaScript to create and modify visual elements.**

```
<canvas id="app" width="400px" height="400px"></canvas>
```
## Javascript To Control Canva Module One

### Drow the line

```
ctx.moveTo(0, 0);
ctx.lineTo(300, 300);
ctx.stroke();
```
### Drow the Box

```
<script>
let canvas = document.getElementById('app');
let ctx = canvas.getContext('2d');

ctx.fillStyle = 'royalblue';
ctx.fillRect(50, 50, 200, 200);


</script>

```
