# eSharp Beta
A easy to use html canvas based helper tool/software/game engine.<br/>
# New commands in development <br/>
<details>
  <summary>es.chooseRandom(op1,op2,op3,op4);</summary>
  <ul>
    <li>
      <b>The code for the event </b><br/>
----chooseRandom(x,y,z,d){<br/>
--------let choosed = this.random(5);<br/>
--------if(choosed == 0){choosed++;}<br/>
--------if(choosed == 1){return x;}<br/>
--------if(choosed == 2){return y;}<br/>
--------if(choosed == 3){return z;}<br/>
--------if(choosed == 4){return d;}<br/>
----}<br/>
 </li>
    <li>
      <b>A way to use it</b><br/>
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
    <li>es.ellipse(x,y,radius,color,opacity);</li>
    <li>es.clear();</li>
    <li>es.background(color);</li>
    <li>es.image(image,x,y,width,height,opacity);</li>
    <li>es.checkCollisions(x,y,width,height,x1,y1,width1,height1);</li>
    <li>es.text("text",x,y,color,opacity);</li>
    <li>es.line(x,y,x1,y1,lineWidth,color,opacity);</li>
    <li>es.getMousePos(canvas,event);</li>
	</ul>
</details><br/>
The Opacity selector is optional <br/>
More things coming soon.<br />



