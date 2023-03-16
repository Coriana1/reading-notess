##HTML Forms

#Your first Web Form. How To Structure A Web Form.
1. Why are forms so important in web development?
    - Forms are a good way to capture your website visitors' details - **such as: email, name, feedback, ect.** They also help visitors get in contact with a company, place orders, and sned request or inquiries. 
2. When designing a form, what are some key things to keep in mind when it comes to user experience?
    - Keep In Mind: *less is more, communicate errors clearly, be simple & straightforward, use clear titles, align text to the left*
3. List 5 form elements and explain their importance.
    * 1. <input> creates interactive controls for web-based forms in order to accept data from the users
    * 2  <label> defines lables, used for screen-reader users (will read out loud the label when the user focuses on the input element), helps useres who have difficulty clicking on small regions
    * 3  <legend> adds caption for the content of a group of related form <input> elements
    * 4  <select> creates a dropdown list of options (users can pick one or multiple)
    * 5  <button> allows useres to submit the filled form to the server for processing


# Learn JS - Introduction To Events.
1. How would you describe events to a non-technical friend?
    - When the webpage loads that is an event. It is when all of the behind the scenes HTML and Javascript occur and the browser page is now manipulated to what you see. 
2. When using the addEventListener() method, what 2 arguments will you need to provide?
    - The event and the handler
3. Describe the event object. Why is the target within the event object useful?
    - Target is a property of an event object (holds information about something that's happened to it's source) that refers to the element that triggered the event. This identifies which element an event originated from, which is often necessary when working with event listeners.
4. What is the difference between event bubbling and event capturing?
    - One happens after the other, the user interacts with an element aka the capturing phase (the DOM API traverses down the document) to the target element, then the DOM API traverses up again which is the bubbling phase. 
