# eSharp Beta
A easy to use html canvas based helper tool/software/game engine.<br/>
# New commands in development <br/>
<details>
  <summary>es.getMousePos(canvas, event);</summary>
  <ul>
    <li>
      <b>The code for the event </b><br/>
-----getMousePos(canvas, event) {<br/>
---------var rect = canvas.getBoundingClientRect();<br/>
---------return {<br/>
-------------x: event.clientX - rect.left;<br/>
-------------y: event.clientY - rect.top;<br/>
---------};<br/>
    }</li>
    <li>
      <b>A way to use it</b><br/>
      <img src = "screenshots/main2.png"><br/>
      <img src = "screenshots/main.png">
    </li>  
  </ul>
</details><br/>
<br/>
<b>Main Commands</b> <br/>
<details> 
	<summary>Commands</summary>
	<br>
	<ul>
    <li>es.random(maximum number);</li>
    <li>es.end();</li>
    <li>es.print("what is said"); </li>
    <li>es.rect(x,y,width,height,color,opacity);</li>
    <li>es.eclipse(x,y,radius,color,opacity);</li>
    <li>es.clear();</li>
    <li>es.background(color);</li>
    <li>es.image(image,x,y,width,height,opacity);</li>
    <li>es.checkCollisions(x,y,width,height,x1,y1,width1,height1);</li>
    <li>es.text("text",x,y,color,opacity);</li>
    <li>es.line(x,y,x1,y1,lineWidth,color,opacity);</li>
	</ul>
</details><br/>
The Opacity selector is optional <br/>
More things coming soon.<br />



