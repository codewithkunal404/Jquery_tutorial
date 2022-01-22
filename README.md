# <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcTXWDt5XmFhzjVTL9nNutcGaRFTIHJArLuc-pmCuyYiuxVl7RWW3xasxSiSN8w3iE8nSPE&usqp=CAU" width="100px"> Jquery_tutorial


<br>
<br>

># A. Introduction 🧑‍💻


  jQuery is a lightweight, "write less, do more", JavaScript library.

The purpose of jQuery is to make it much easier to use JavaScript on your website.

jQuery takes a lot of common tasks that require many lines of JavaScript code to accomplish, and wraps them into methods that you can call with a single line of code.

jQuery also simplifies a lot of the complicated things from JavaScript, like AJAX calls and DOM manipulation. 


<br> 
<br>

># B. jQuery CDN path 
    
     <script src="https://ajax.googleapis.com/ajax/libs/jquery/3.5.1/jquery.min.js"></script>

<br>
<br>

># C. Syntax

Basic syntax is: $(selector).action()



 <li> A $ sign to define/access jQuery</li>
 <li> A (selector) to "query (or find)" HTML elements</li>
  <li> A jQuery action() to be performed on the element(s)</li>

## The Document Ready Event:::


You might have noticed that all jQuery methods in our examples, are inside a document ready event:

#### type1:

      $(document).ready(function(){

       // jQuery methods go here...

       });
       

#### type2:

      $(function(){

       // jQuery methods go here...

       });

### Examples:

$(this).hide() - hides the current element.

$("p").hide() - hides all elements.


<img src="https://cdn-icons-png.flaticon.com/512/1384/1384060.png" width="30px">::: https://youtu.be/HE_4DjvvJGs

<br>
<br>


># D. Selectors
<li>ALL selector $(*)</li>
<li>Current selector $(this)</li>
<li>Class selector $(".class")</li>
<li>Element selector $("p")</li>
<li>Id selector $("#id")</li>
<li>Attribute selector $("input[type="text"]")</li>
<br>
  Example:
  
  <a href="https://codewithkunal404.github.io/Jquery_tutorial/allselector.html">RunCode</a>///////////
  <a  href="https://github.com/codewithkunal404/Jquery_tutorial/blob/main/allselector.html">SourceCode</a>
  
  
<img src="https://cdn-icons-png.flaticon.com/512/1384/1384060.png" width="30px">:::https://youtu.be/Pw9i4H2PsYI
  
  <br>
  <br>
  
># E. What are Events?



       All the different visitors' actions that a web page can respond to are called events.
       An event represents the precise moment when something happens.
      
       Examples:

       moving a mouse over an element
       selecting a radio button
       clicking on an element

#### Here are Various Types?

<li>blur()</li>
<li>click()</li>
<li>dbclick()</li>
<li>focus()</li>
<li>focusin()</li>
<li>focusout()</li>
<li>hover()</li>
<li>mousedown()</li>
<li>mouseleave()</li>
<li>mousemove()</li>	
<li>mouseout()</li>
<li>mouseover()</li>
<li>mouseup()</li>
<li>toggle()</li>
<li>submit()</li>
<li>scroll()</li>
<li>keyup()</li>
<li>keydown()</li>
<li>keypress()</li>
<li>select()</li>
<br>
 Example:
  
  <a href="https://codewithkunal404.github.io/Jquery_tutorial/allevents.html">RunCode</a>///////////
  <a  href="https://github.com/codewithkunal404/Jquery_tutorial/blob/main/allevents.html">SourceCode</a>



  
<img src="https://cdn-icons-png.flaticon.com/512/1384/1384060.png" width="30px">::part-1: https://youtu.be/wV08YuMpzCA

<img src="https://cdn-icons-png.flaticon.com/512/1384/1384060.png" width="30px">::part-2: https://youtu.be/L0rfjYdvWzg

<img src="https://cdn-icons-png.flaticon.com/512/1384/1384060.png" width="30px">::part-3:   https://youtu.be/B3q0FPB8R3w

  <br>
  <br>
  
># F. Jquery Effects?

### Show/Hide

<li>Show()</li>
<li>Hide()</li>
<li>Toggle()</li>

Example:
  
  <a href="https://codewithkunal404.github.io/Jquery_tutorial/showhide.html">RunCode</a>///////////
  <a  href="https://github.com/codewithkunal404/Jquery_tutorial/blob/main/showhide.html">SourceCode</a>
  
  
<img src="https://cdn-icons-png.flaticon.com/512/1384/1384060.png" width="30px">::: https://youtu.be/OoCZBg1HY_M

### Fade
<li>fadeIn()</li>
<li>fadeOut()</li>
<li>fadeToggle()</li>
<li>fadeTo()</li>

Example:
  
  <a href="https://codewithkunal404.github.io/Jquery_tutorial/fade.html">RunCode</a>///////////
  <a  href="https://github.com/codewithkunal404/Jquery_tutorial/blob/main/fade.html">SourceCode</a>
  
  
  
<img src="https://cdn-icons-png.flaticon.com/512/1384/1384060.png" width="30px">::: https://youtu.be/vkPULgC8Ulo 
 
### Slide
<li>slideDown()</li>
<li>slideUp()</li>
<li>slideToggle()</li>

Example:
  
  <a href="https://codewithkunal404.github.io/Jquery_tutorial/slide.html">RunCode</a>///////////
  <a  href="https://github.com/codewithkunal404/Jquery_tutorial/blob/main/slide.html">SourceCode</a>
  
  
<img src="https://cdn-icons-png.flaticon.com/512/1384/1384060.png" width="30px">::: https://youtu.be/RrSgsSqvZVw

### animate
<li>jQuery animate() - Manipulate Multiple Properties</li>
<li>jQuery animate() - Using Relative Values</li>
<li>jQuery animate() - Using Pre-defined Values</li>
<li>jQuery animate() - Uses Queue Functionality</li>


Example:
  
  <a href="https://codewithkunal404.github.io/Jquery_tutorial/animate.html">RunCode</a>///////////
  <a  href="https://github.com/codewithkunal404/Jquery_tutorial/blob/main/animate.html">SourceCode</a>
 



<img src="https://cdn-icons-png.flaticon.com/512/1384/1384060.png" width="30px">:::   https://youtu.be/pgs_boB89Xo

### stop
<li>stop() sliding</li>
<li>stop() animation</li>

Example:
  
  <a href="https://codewithkunal404.github.io/Jquery_tutorial/stop.html">RunCode</a>///////////
  <a  href="https://github.com/codewithkunal404/Jquery_tutorial/blob/main/stop.html">SourceCode</a>

### callback
<li>with callback</li>
<li>without callback</li>

Example:
  
  <a href="https://codewithkunal404.github.io/Jquery_tutorial/callback.html">RunCode</a>///////////
  <a  href="https://github.com/codewithkunal404/Jquery_tutorial/blob/main/callback.html">SourceCode</a>

### Chaining
<li> .css().slideup().slidedown().........</li>
<br>

Example:
  
  <a href="https://codewithkunal404.github.io/Jquery_tutorial/chaining.html">RunCode</a>///////////
  <a  href="https://github.com/codewithkunal404/Jquery_tutorial/blob/main/chaining.html">SourceCode</a>



<br>
<br>



># G. Jquery HTML



### Jquery Get
<li>html()</li>
<li>text()</li>
<li>val()</li>
<li>attr()</li>


Example:
  
  <a href="https://codewithkunal404.github.io/Jquery_tutorial/get.html">RunCode</a>///////////
  <a  href="https://github.com/codewithkunal404/Jquery_tutorial/blob/main/get.html">SourceCode</a>
  
  



### Jquery Set
<li>html()</li>
<li>text()</li>
<li>val()</li>
<li>attr()</li>




Example:
  
  <a href="https://codewithkunal404.github.io/Jquery_tutorial/set.html">RunCode</a>///////////
  <a  href="https://github.com/codewithkunal404/Jquery_tutorial/blob/main/set.html">SourceCode</a>




### Jquery Add
<li>append() </li>
<li>prepend()</li>
<li>after() </li>
<li>before() </li>

Example:
  
  <a href="https://codewithkunal404.github.io/Jquery_tutorial/add.html">RunCode</a>///////////
  <a  href="https://github.com/codewithkunal404/Jquery_tutorial/blob/main/add.html">SourceCode</a>






### Jquery Remove
<li>remove()</li>
<li>empty()</li>

Example:
  
  <a href="https://codewithkunal404.github.io/Jquery_tutorial/remove.html">RunCode</a>///////////
  <a  href="https://github.com/codewithkunal404/Jquery_tutorial/blob/main/remove.html">SourceCode</a>






### Jquery Css Classes
<li>addClass()</li>
<li>removeClass()</li>
<li>toggleClass()</li>
<li>css()</li>

Example:
  
  <a href="https://codewithkunal404.github.io/Jquery_tutorial/cssclass.html">RunCode</a>///////////
  <a  href="https://github.com/codewithkunal404/Jquery_tutorial/blob/main/cssclass.html">SourceCode</a>




### Jquery css()
<li>Return a CSS Property</li>
<li>Set a CSS Property</li>
<li>Set Multiple CSS Properties</li>

 
Example:
  
  <a href="https://codewithkunal404.github.io/Jquery_tutorial/css.html">RunCode</a>///////////
  <a  href="https://github.com/codewithkunal404/Jquery_tutorial/blob/main/css.html">SourceCode</a> 
  
  
  


### Jquery Dimension 
  
<li>width()</li>
<li>height()</li>
<li>innerWidth()</li>
<li>innerHeight()</li>
<li>outerWidth()</li>
<li>outerHeight()</li>

Example:
  
  <a href="https://codewithkunal404.github.io/Jquery_tutorial/chaining.html">RunCode</a>///////////
  <a  href="https://github.com/codewithkunal404/Jquery_tutorial/blob/main/chaining.html">SourceCode</a> 
  
  




