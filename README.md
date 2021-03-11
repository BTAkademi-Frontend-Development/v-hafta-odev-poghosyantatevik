# v-hafta-odev

- aria labellarla ilgili araştırmalar yapıp sonucçlarını yazınız. Birkaç örneği deneyerek ilgili reponun linkini veriniz.
  
  :dart: Aria is the short version of WAI-ARIA, which stands for “Web Accessibility Initiative – Accessible Rich Internet Applications”.
         Web accessibility domain defines how to make web content usable by people with disabilities. People with certain types of disabilities use assistive technologies to interact with content. Assistive technologies can change the presentation of content into a format that is more suitable to the user, and can allow the user to interact in different ways. For example,  we know that everyone loves carousels. An image comes after image making the products more interesting for the clients but generally carousels should be avoided as they can be confusing for screen readers. Important information is placed on images, the rapid changing of the images can also cause seizures.
To avoid this it is better to avoid carousels, or follow some simple steps, such as longer transform duration, image with en emphasised link at the bottom and there are not more than 5 images a carousel.

**The three main components of ARIA are roles, properties, and states.**

**Roles** define what an element is or does. Most HTML elements have a default role that is presented to assistive technology. For example, <button> has a default role of "button" and <form> has a default role of "form". ARIA can define roles that are not available in HTML, and can also override the default roles of HTML elements.
   
ARIA **properties** define additional semantics not supported in standard HTML. An example is <button aria-haspopup="true">. This property extends the standard button to cause a screen reader to announce that the button, if activated, will trigger a pop-up.
   
ARIA **states** are attributes that define the current condition of an element. They generally change based on user interaction or some dynamic variable. An example is <input aria-invalid="true">. This property will cause a screen reader to read this input as currently being invalid (meaning it needs to be corrected), but this state value could easily be changed to false dynamically based on user input.
   
 **Links I used:**
 
 [Introduction to ARIA](https://webaim.org/techniques/aria/)
 
 [A11Y-101](https://a11y-101.com/development/aria-label)
 
 

- Derste yapılan örneği kişiselleştirerek reponun linkini ekleyiniz.

  :dart: some changes have been made, more to come (https://github.com/poghosyantatevik/classwork.git)

- JavaScript'te var/let/const keywordleri arasındaki farkları açıklayınız.

   :dart: VAR was the original variable declaration in JS, but because JS was created within a short period of time, there were some drawbacks in it, here ES6, released in 2015 came quite handy, as at that time LET and CONST were introduced which are block level elements, unlike VAR which scope is global. One of the main problems of being global, is that the declared values can overwrite a declaration, avoiding such problems required extra attention, and because of that LET and CONST came into play. 
   When we assign a value to a variable with CONST, later on another value can not be given to that variable within its block scope. Another important point is that JS const variables must be assigned a value when they are declared, they can later be changed, but never reassigned. 
   
   e.g. below example will given an error
   
   **const building = {type:"condos", year:"1961", color:"gray"};
   
   **building = {type:"bungalows", year:"1994", color:"white"};    // ERROR
   
  LET is like CONST, in a way that it's also accessable only in a block scope and like VAR a value can later be assigned to it,in this instance unlike CONST variable. 
   e.g below example will work
   
   **let ageOfGirl = 20;**
   
    **ageOfGirl = 22;**
    
    **console.log(ageOfGirl);** output 22 
    
    
    e.g. this example wont work
    
     **let ageOfGirl = 20;**
     
    **let ageOfGirl = 22;**
    
    **console.log(ageOfGirl);** (ERROR - Identifier 'ageOfGirl' has already been declared)
    
   Unlike LET, VAR  gives the advantage to declare the variable as many times as needed.
   
  See below example: 
  
  **var daysOfTheYear = 365;**
  
  **var daysOfTheYear = 366;**
  
  **console.log(daysOfTheYear);** // (this will work and the result wil be 366)
  
   here are the resources that I have used: 
   
   [Var, Let, and Const – What's the Difference?](https://www.freecodecamp.org/news/var-let-and-const-whats-the-difference/#:~:text=var%20declarations%20are%20globally%20scoped%20or%20function%20scoped%20while%20let,be%20updated%20nor%20re%2Ddeclared.)
   
   [JavaScript Const](https://www.w3schools.com/js/js_const.asp)
   
   [Const vs Let vs Var in Javascript. Which One Should You Use?](https://levelup.gitconnected.com/const-vs-let-vs-var-in-javascript-which-one-should-you-use-c56cf9b9e2a3)
