# <center>Entry 2: CodeAcademy</center>
<p>In order to grow my knowledge of <b>React JS</b>, 
I continued to take courses on <em>Codecademy</em>. The practice examples, important lessons,
and quizzes provided by <em>Codecademy</em> were extremely helpful in the process of learning and becoming more comfortable with the language. </p>
<p>When I began my second week of independent study, I was only scratching the surface of what <b>React JS</b> can really do. 
This week was dedicated to growing my knowledge of the basics, as well as, discovering some projects that could be 
developed utilizing <b>React JS</b>.
So I sat myself down in front of the computer, mentally prepared myself
for the week ahead, and told myself...</p>

<img src="../entries/images/learntoday.jpeg" style="height:100px, width: 200px;" />

<p>While taking <em>Codecademy</em> lessons, I learned a few basic rules. For instance,
I learned that JSX will only treat numbers as numbers if they are wrapped 
around curly braces, otherwise, it will see it as a string. 
I tested this rule in an example that consisted of getting the screen 
to display the result of 2+3. 

```ReactDOM.render(<h1>{2 + 3}</h1>,document.getElementById('app'));```
	
This line of code renders, or displays, an h1 to the screen. The curly brackets 
make it so that the computer recognizes it as numbers to add together. 
The screen will then display the sum, being the number 5. If the curly 
brackets were not there, the screen would simply display 2+3, because it
would be seeing it as a string. You would also use curly brackets for a 
variable.

While studying on <em>Codecademy</em>, I would compare new knowledge
to my own prior knowledge. For instance, I recognized, through 
looking at the example code provided by Codecademy, that if 
else statements in JSX do not have an end, it is simply and if/else 
statement. 

Also, ```React.createClass()```creates a component class that is like a factory for 
creating React components, similar to the way I had viewed 
classes in ruby that create objects. Also, in order to use this method, 
you must include```var React = require('react')```
within your file, as it allows access to certain react methods. 

Additionally, JSX uses keys, which are very similar to ids. 
For example, within a tag you might put ```id=””``` but in 
JSX, you would put ```key= “value”```. I found out that lists 
use keys in order to remember the item. Keys are especially useful 
when making To Do Lists in JSX, so that the code will remember what 
items were checked off. 
____

Next, I tried out an example on Codecademy that involved
clicking on an image of a kitten to get a picture of a dog to appear. 
I solved the example utilizing the information provided by the lesson, 
then looked over the code to make sure I understood every part. 
```
function makeDoggy(e) {
    e.target.setAttribute('src', 'https://s3.amazonaws.com/codecademy-content/courses/React/react_photo-puppy.jpeg');
    e.target.setAttribute('alt', 'doggy');```
    function makeDoggy(e) {
    e.target.setAttribute('src', 'https://s3.amazonaws.com/codecademy-content/courses/React/react_photo-puppy.jpeg');
    e.target.setAttribute('alt', 'doggy');
}'

```

So basically what the function ```makeDoggy``` does is it gets a target, the target being an image. In other words, to make the doggy, the computer must find the image of the doggy

```
var kitty = (
	<img onClick={makeDoggy}
	
```
This event listener is embedded into the image, so that when the image itself is clicked, the function ```makeDoggy``` will run
```
src="https://s3.amazonaws.com/codecademy-content/courses/React/react_photo-kitty.jpg" 
		alt="kitty" />
);

```

This is the image of the kitty that is set to the variable named kitty

```ReactDOM.render(kitty, document.getElementById('app'));```

This line of code displays the picture of the kitty and activates 
the event listener.
From this example, I also learned more about closing tags in JSX, because 
for tags like ```<br>``` or ```<img>``` that you wouldn’t normally see with 
closing tags, actually need a closing slash. Also, there must be a space 
before the closing slash, like so:

```<br />    <img />```

The event listening I learned in this example, I thought could come in handy for my future project or perhaps a cool feature to add to a website. 

Lastly, I learned that <b>React JS</b> can be written without JSX.
For example,

<b>Without JSX:</b>

```
var h1 = React.createElement(
	  "h1",
 	 null,
 	 "Hello, world"
	);
```
	
<b>With JSX:</b>
```
var h1 = <h1>Hello world</h1>;
```
Although it is possible to code without JSX, I find that coding 
<em>with</em> JSX is much more efficient. </p>

### <strong>Takeaways</strong>
<ul>
    <li>Whenever you are faced with something you do not understand, to
    make it easier, it is helpful to <b>break it down</b>. 
    Step by step is the way to go! <b>Every step matters, no matter how small</b>.
    In terms of coding,
    I found that it is beneficial to break apart each line of code and analyze it
    so that I can better understand the meaning or purpose of each part.
    </li>
    <li><b>Practice, Practice, Practice!</b> The more you practice, the more you know.
    The more you know, the more you grow.</li>
</ul>
<img src="../entries/images/dory.jpg" />
<img src="../entries/images/yoda-learn.jpg"/>
