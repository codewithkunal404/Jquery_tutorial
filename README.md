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

<br>
<br>


># D. Selectors
<li>ALL selector $(*)</li>
<li>Current selector $(this)</li>
<li>Class selector $(".class")</li>
<li>Element selector $("p")</li>
<li>Id selector $("#id")</li>
<li>Element selector $("p")</li>
<li>Attribute selector $("input[type="text"]")</li>

  Example:
  
  <a href="">RunCode</a>///////////<a href="">SourceCode</a>
  
