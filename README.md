># Jquery_tutorial

<img src="https://github.com/codewithkunal404/Jquery_tutorial/blob/main/jquery-3-3-1-cdn.png" width="500px">


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
  
  
  

<img src="https://cdn-icons-png.flaticon.com/512/1384/1384060.png" width="30px">:::   https://youtu.be/gQbdc_bmA3s




### callback
<li>with callback</li>
<li>without callback</li>

Example:
  
  <a href="https://codewithkunal404.github.io/Jquery_tutorial/callback.html">RunCode</a>///////////
  <a  href="https://github.com/codewithkunal404/Jquery_tutorial/blob/main/callback.html">SourceCode</a>





<img src="https://cdn-icons-png.flaticon.com/512/1384/1384060.png" width="30px">:::  https://youtu.be/IJ08Bn0Ca5Y



### Chaining
<li> .css().slideup().slidedown().........</li>
<br>

Example:
  
  <a href="https://codewithkunal404.github.io/Jquery_tutorial/chaining.html">RunCode</a>///////////
  <a  href="https://github.com/codewithkunal404/Jquery_tutorial/blob/main/chaining.html">SourceCode</a>
  
  <br>
  

<img src="https://cdn-icons-png.flaticon.com/512/1384/1384060.png" width="30px">:::   https://youtu.be/yxTCE5I_dos
  



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
  
  
<img src="https://cdn-icons-png.flaticon.com/512/1384/1384060.png" width="30px">:::  https://youtu.be/_Svt22ozoYg
  
  
  



### Jquery Set
<li>html()</li>
<li>text()</li>
<li>val()</li>
<li>attr()</li>




Example:
  
  <a href="https://codewithkunal404.github.io/Jquery_tutorial/set.html">RunCode</a>///////////
  <a  href="https://github.com/codewithkunal404/Jquery_tutorial/blob/main/set.html">SourceCode</a>




  
<img src="https://cdn-icons-png.flaticon.com/512/1384/1384060.png" width="30px">:::  https://youtu.be/YaiEIASC2Uw



### Jquery Add
<li>append() </li>
<li>prepend()</li>
<li>after() </li>
<li>before() </li>

Example:
  
  <a href="https://codewithkunal404.github.io/Jquery_tutorial/add.html">RunCode</a>///////////
  <a  href="https://github.com/codewithkunal404/Jquery_tutorial/blob/main/add.html">SourceCode</a>
  
  
  
    
<img src="https://cdn-icons-png.flaticon.com/512/1384/1384060.png" width="30px">::: https://youtu.be/PTM-yl4qqfc






### Jquery Remove
<li>remove()</li>
<li>empty()</li>

Example:
  
  <a href="https://codewithkunal404.github.io/Jquery_tutorial/remove.html">RunCode</a>///////////
  <a  href="https://github.com/codewithkunal404/Jquery_tutorial/blob/main/remove.html">SourceCode</a>



<img src="https://cdn-icons-png.flaticon.com/512/1384/1384060.png" width="30px">::: https://youtu.be/9VXj8yMpkcg





### Jquery Css Classes
<li>addClass()</li>
<li>removeClass()</li>
<li>toggleClass()</li>
<li>css()</li>

Example:
  
  <a href="https://codewithkunal404.github.io/Jquery_tutorial/cssclass.html">RunCode</a>///////////
  <a  href="https://github.com/codewithkunal404/Jquery_tutorial/blob/main/cssclass.html">SourceCode</a>


<img src="https://cdn-icons-png.flaticon.com/512/1384/1384060.png" width="30px">::: https://youtu.be/0qwTkW2CzH8


### Jquery css()
<li>Return a CSS Property</li>
<li>Set a CSS Property</li>
<li>Set Multiple CSS Properties</li>

 
Example:
  
  <a href="https://codewithkunal404.github.io/Jquery_tutorial/css.html">RunCode</a>///////////
  <a  href="https://github.com/codewithkunal404/Jquery_tutorial/blob/main/css.html">SourceCode</a> 
  
  
  
<img src="https://cdn-icons-png.flaticon.com/512/1384/1384060.png" width="30px">::: https://youtu.be/Dx3gV9nxt5o

### Jquery Dimension 
  
<li>width()</li>
<li>height()</li>
<li>innerWidth()</li>
<li>innerHeight()</li>
<li>outerWidth()</li>
<li>outerHeight()</li>

Example:
  
  <a href="https://codewithkunal404.github.io/Jquery_tutorial/dimension.html">RunCode</a>///////////
  <a  href="https://github.com/codewithkunal404/Jquery_tutorial/blob/main/dimension.html">SourceCode</a> 
  
  
  
  
<img src="https://cdn-icons-png.flaticon.com/512/1384/1384060.png" width="30px">::: https://youtu.be/LK2xOgaqPyc

<br>

># H. Jquery noConflict() Method

<li>The noConflict() method releases the hold on the $ shortcut identifier, so that other scripts can use</li>
<br>

Example:
  <a href="https://codewithkunal404.github.io/Jquery_tutorial/noconflict.html">RunCode</a>///////////
  <a  href="https://github.com/codewithkunal404/Jquery_tutorial/blob/main/noconflict.html">SourceCode</a> 


<img src="https://cdn-icons-png.flaticon.com/512/1384/1384060.png" width="30px">::: https://youtu.be/8wStwd56BOA
<br>

># I. Jquery Traversing

<li>jQuery traversing, means accessing a particular type of  element according to their relation with other elements such as child,parent,grandparent etc.</li>
<br>
<img src="https://github.com/codewithkunal404/Jquery_tutorial/blob/main/mom.png" width="300px">

### JQuery Traversing 

     👉  The <div> element is the parent of <ul>, and an ancestor of everything inside of it
     
     👉  The <ul> element is the parent of both <li> elements, and a child of <div>
     
     👉  The <li> element is the parent of <span>, child of <ul> and a descendant of <div>
     
     👉 The two left and right <span> element is a child of the <li> and a descendant of <ul> and <div>
     
     👉  left and right <span> are siblings childs which is  childs  of its same parent <li>
     
     

<br>
<img src="https://cdn-icons-png.flaticon.com/512/1384/1384060.png" width="30px">:::https://youtu.be/b_EVovod_Mk

<br>


## JQuery Ancestors : An ancestor is a parent, grandparent, great-grandparent, and so on.

<li>parent()</li>
<li>parents()</li>
<li>parentsUntil()</li>

<br>
Example:
  
  <a href="https://codewithkunal404.github.io/Jquery_tutorial/ancestor.html">RunCode</a>///////////
  <a  href="https://github.com/codewithkunal404/Jquery_tutorial/blob/main/ancestor.html">SourceCode</a> 
  <br>
  
  <img src="https://cdn-icons-png.flaticon.com/512/1384/1384060.png" width="30px">::: https://youtu.be/4DNmreUSTaU

<br>

## JQuery Descendants : A descendant is a child, grandchild, great-grandchild, and so on. 

<li>children()</li>
<li>find()</li>

<br>
Example:
  
  <a href="https://codewithkunal404.github.io/Jquery_tutorial/descendant.html">RunCode</a>///////////
  <a  href="https://github.com/codewithkunal404/Jquery_tutorial/blob/main/descendant.html">SourceCode</a> 
  <br>
  <img src="https://cdn-icons-png.flaticon.com/512/1384/1384060.png" width="30px">::: https://youtu.be/BNVozn6BqWg
  <br>
  
## JQuery Sibling : Siblings share the same parent. 


<li>siblings()</li>
<li>next()</li>
<li>nextAll()</li>
<li>nextUntil()</li>
<li>prev()</li>
<li>prevAll()</li>
<li>prevUntil()</li>

<br>

Example:
  
  <a href="https://codewithkunal404.github.io/Jquery_tutorial/sibling.html">RunCode</a>///////////
  <a  href="https://github.com/codewithkunal404/Jquery_tutorial/blob/main/sibling.html">SourceCode</a> 
  
  <br>
  

## Jquery Filtering  : in which allow you to select a specific element based on its position in a group of elements.



<li>first()- method returns the first element of the specified elements.</li>
<li>last()-method returns the last element of the specified elements.</li>
<li>eq()-method returns an element with a specific index number of the selected elements.</li>
<li>filter()-method returns an element that you have to choose and match the criteria </li>
<li>not()- method returns all elements that do not match the criteria.</li>


<br>

Example:
  
  <a href="https://codewithkunal404.github.io/Jquery_tutorial/filtering.html">RunCode</a>///////////
  <a  href="https://github.com/codewithkunal404/Jquery_tutorial/blob/main/filtering.html">SourceCode</a> 
  
<br>
  
