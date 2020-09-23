<div align="center">

## Visual D\+\+ 4\.1


</div>

### Description

A new generation of D++ is here, now you can code visual D++ applications, yeah thats right with forms and everything!
 
### More Info
 


<span>             |<span>
---                |---
**Submitted On**   |
**By**             |[Paul J\. Murphy](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByAuthor/paul-j-murphy.md)
**Level**          |Intermediate
**User Rating**    |4.8 (63 globes from 13 users)
**Compatibility**  |VB 6\.0
**Category**       |[Complete Applications](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByCategory/complete-applications__1-27.md)
**World**          |[Visual Basic](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByWorld/visual-basic.md)
**Archive File**   |[](https://github.com/Planet-Source-Code/paul-j-murphy-visual-d-4-1__1-54298/archive/master.zip)





### Source Code

<html>
<p>After 2 weeks of programming i have finally finished Visual D++ 2.0. This is
based on D++ 4.1, but because D++ 4.1 is just a text based programming language,
i decided to give it command buttons, text boxes, list boxes etc. <br>
I loosely based it on PowerBasics DDT, it looks the same although its quite
diffrent so i guess it cant really be called DDT, but its still really simple to
code with it, here is an example of code:<br>
function main()<br>
{<br>
vdpp;<br>
control add form 0 3825 1635 6630 to Form1;<br>
control set Form1 form text to &quot;Donuts DDE mIRC send&quot;;<br>
control set Form1 form backcolor to &quot;15279930&quot;;<br>
control add Form1 label 144.4126 60.38464 396.6262 4574.137 to Label1; <br>
control set Form1 label Label1 text to &quot;Enter command you want to send to mIRC:&quot;;
<br>
control set Form1 label Label1 backcolor to &quot;15279930&quot;;<br>
control set Form1 label Label1 forecolor to &quot;2152936&quot;;<br>
control add Form1 command 1409.549 392.5002 762.7427 9053.167 to Command1;<br>
control set Form1 command Command1 text to &quot;Send to mIRC&quot;;<br>
control add Form1 text 671.2136 75.4808 579.6845 9700.793 to text1;<br>
control set Form1 text text1 text to &quot;&quot;;<br>
control set Form1 text text1 backcolor to &quot;65280&quot;;<br>
}<br>
function Form1()<br>
{<br>
if Form1 = &quot;UNLOAD&quot; then<br>
end;<br>
endif;<br>
}<br>
function Command1()<br>
{<br>
if command1 = &quot;CLICK&quot; then<br>
newvar tosend;<br>
control get Form1 text text1 text to tosend;<br>
control set Form1 text text1 linksetting to &quot;mIRC|command&quot;;<br>
control set Form1 text text1 linkmode to &quot;0&quot;;<br>
control set Form1 text text1 linkitem to tosend;<br>
control set Form1 text text1 linkmode to &quot;2&quot;;<br>
control set Form1 text text1 linkpoke;<br>
control set Form1 text text1 linkmode to &quot;0&quot;;<br>
control set Form1 text text1 text to &quot;&quot;;<br>
endif;<br>
}<br>
90% of that code is already programmed with the Visual IDE that i made, so you
can just draw forms yourself, and place objects on it.<br>
Here is the download location: <br>http://donut.pagemac.com/vdpp2.zip<br>
Unfortunately PSC doesnt allow links<br>
Because d++ depends on a dppsecurity.dll to prevent other people ripping the
entire progamming language and putting their own name on it, so i cant upload it
to Planetsourcecode, but its completly virus free (i checked).<br>
Please note: If you do vote, vote for the visual features and the code in
modDDT.bas, and the visual ide but not for the rest as the rest is all SquekMac's/Azures code, and please give us a visit on the pagemac forums,
http://forums.pagemac.com
D++ is getting more and more active now.<br>
http://www.pagemac.com/</p>
</html>

