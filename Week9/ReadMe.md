# NYU Digital Art for Non-Majors, Wk9
##p5 Lecture Notes

_Outline:_
* Intros & Sign-in
* Intro to p5
	* What is it?
	* What have people done with “Creative Code”?
* HELLO WORLD
	* Set up accounts in p5 editor:
	* [p5.js Web Editor](https://editor.p5js.org)
		* https://editor.p5js.org
	* The basics of drawing (shapes)
		* rect(x, y, w, h);
		* ellipse(x, y, w, h);
		* line(x1, y1, x2, y2);
	* The basics of color:
		* background();
		* stroke();
		* strokeWeight();
		* fill():
		* RGB: 0-255, 1 value, 3 values, 4 values.
	* Comments : 
	* Order of Operations

* Dan Shiffman videos for reference:
	* [1.3: Shapes & Drawing - p5.js Tutorial - YouTube](https://www.youtube.com/watch?v=c3TeLi6Ns1E&index=3&list=PLRqwX-V7Uu6Zy51Q-x9tMWIv9cueOFTFA)
	* [1.4: Color - p5.js Tutorial - YouTube](https://www.youtube.com/watch?v=riiJTF5-N7c&index=4&list=PLRqwX-V7Uu6Zy51Q-x9tMWIv9cueOFTFA)
* Links
	* [Processing’s Exhibitions Page](https://processing.org/exhibition/) (Processing is what p5 is based on)
* Artists & Designers who have used Processing:
	* Nils Volker's “[One Hundred And Eight](http://nilsvoelker.com/content/onehundredandeight/index.html)" (Kinetic Sculpture)
	* Mary Huang’s “[Continuum](http://www.rhymeandreasoncreative.com/portfolio/index.php?project=continuum)” (Generative Fashion & Sculpture)
	* [The Feltron Reports](http://feltron.com/FAR11.html) (Data Visualization)
	* Michael Hansmeyer's “[Platonic Solids](http://www.michael-hansmeyer.com/platonic-solids#1)" (Generative 3D scultures)
	* [MTV Brazil Identity 2009](http://dmtr.org/mtv_rewind/)
	* Casey Reas’ “[Process Compendium](https://vimeo.com/22955812)” (works from 2004-2010)



### Example:
```
function setup() {
  createCanvas(600, 600);
}

function draw() {
  background(200);
  
  fill(100,200,10);
  ellipse(300,250,300,200);
  
  fill(200,20,100,100);
  stroke(0);
  strokeWeight(5);
  rect(200,200,60,60);
  rect(220,220,60,60);
  rect(240,210,60,60);
  strokeWeight(0);
  ellipse(250,250,100,100);
}
```


Reference Tags:
#Ed_F18 Copied on 10/19/2018 for #Ed_F18/NYU, #Ed_F18/LectureNotes
Original: MMP100, wk 5-2, Wednesday, 10/10/2018



