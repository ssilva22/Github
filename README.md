# Github

1. What is Semantic HTML? 
 -Semantic HTML is HTML that adds meaning to the webpage.
    2. What is HTML used for? 
    HTML is used to give structure to the website.
    3. What is an attribute and where do we put it? 
      Attributes define additional characteristics or properties that are found in an element and are usually specified in the opening tag
    4. What is the h1 tag used for? How many times should I use it on a page?
    The h1 tag is used to establish the main title of your site, the importance of a title ranges from H1 to H6, H1 being the one with the most importance.For
    good practices it is recommended to add only one H1 tag.
    5. Name two tags that have required attributes
    the image and a element because they both require to refer to something in order to work properly.
    6. What do we put in the head of our HTML document? 
    Usually we add metadata and the stylesheets we would like to link to our HTML site.
    7. What is an id? 
    An ID is a unique attribute that you assign to an element. It isn't recommended to use very often because you can only assign one ID to a given item thus making
    it not reusable.
    8. What elements can I add an id to? 
    Any element but they can't all have the same id.
    9. How many times can I use the same id on a page? 
    Only once per id.
    10. What is a class? 
    It's a reusable attribute used to define various elements in HTML.
    11. What elements can I add a class to? 
    Any elements.
    12. How many times can I use the same class on a page? 
    Any amount of times as it's reusable.
    13. How do I get my link to open in a new tab?
    You have to assign the a href tag a target of "_blank"
    14. What is the alt attribute in the image tag used for? 
    To add the meta-description of the image.
    15. How do I reference an id?
    You write a hash character followed by the ID name
    16. What is the difference between a section and a div
    section groups elements inside of it whereas a div doesn't
    17. What is CSS used for? 
    CSS is what makes your website look beautiful.
    18. How to we select an element? Example - every h2 on the page
    Use a selector with the name of the element like for instance, to reference every h2 on the page just use h2{}and add the attributes inside the 
    brackets.You can also assign a specific class to every h2 element on the page and select it via .selector like this: .class{}
    19. What is the difference between a class and an id? - Give me an example of when I might use each one
    A class is reusable whereas an ID isn't. You will use class most of the time when you need to give the same attributes to a significant amount
    of elements, IDs can be used for circumstances in which you want a specific element to have a trait and you are going to use that tag for
    nothing but that element.
    20. How do we select classes in CSS?
    add a period followed by the name of the class.Example: We have a class named person. In order to select it in CSS we would use .person{}.
    21. How do we select a p element with a single class of “human””?
    You assign the p element a class of human and then select it with CSS.
    22. What is a parent child selector? When would this be useful? 
    A parent selector is the main element with the main characteristics whereas a child selector is a secondary element that inherits the charac
    teristics of a parent element.This would be useful if we maybe want to redesign a parent theme without permanently changing it by copying the
    parent theme into a child theme.
    23. How do you select all links within a div with the class of sidebar?
    you reference the parent element which is the div along with the child element which are the links in the sidebar class.
    24. What is a pseudo selector?
    A pseudo selector is a special selector that selects elements that are in a specific state. like for instance the pseudo-selector :hover. Makes
    the element acquire characteristics in the case the element is hovered.
    25. What do we use the change the spacing between lines?
    We usually use the line-height property
    26. What do we use to change the spacing between letters?
    We usually use the letter-spacing property.
    27. What do we use to to change everything to CAPITALS? lowercase? Capitalize?
    We use the property text-transform and the attribute we would like to give lik for instance if we want to make it all capital case then we do
    text-transform:capitalize;.
    28. How do I add a 1px border around my div that is dotted and black?
    We use  border-top:1px dotted #f00;
    29. How do I select everything on the page? 
    We use * which is the universal selector.
    30. How do I write a comment in CSS?
    /*You write in between these*/
    31. How do I find out what file I am in, when I am using the command line? 
    We can use pwd to print the working directory or ls to list out all of the elements in the directory you are currently located in.
    32. Using the command line - how do I see a list of files/folders in my current folder?
    Using ls.
    33. How do I remove a file via the command line? Why do I have to be careful with this? 
    We use rm but we need to be careful because it won't prompt you on whether you are sure about deleting the file or not
    34. Why should I use version control? 
    It's good to adhere to best practices.
    35. How often should I commit to github?
    As often as you make a change to the file.
    36. What is the command we would use to push our repo up to github? 
    You use git push and git pull.
    37. Walk me through Lambda's git flow. 

Stretch Questions

    1. What is the difference between an inline element and a block element?
    A block-element always starts on a new line and uses a line break to take up all of the width available
    2. What happens when an element is positioned absolutely? 
    It sits on its own layer separate from everything else.
    3. How do I make an element take up only the amount of space it needs but also have the ability to give it a width?
    You can use the Flexbox Model.
    4. Name 3 elements that are diplay block by default, 2 elements that are display inline by default and 1 element that is display inline-block by
    default
    section,body,and head are display block by default,span and p are display inline by default and a is display inline-block by default.
    5. In your own words, explain the box model. What is the "fix" for the box model, in other words, how do we make all elements respect the width 
    we've given them? 
    The box model is supposed to standardize sizing in a website.  It's essentially a box that wraps out every HTML elements



   --> 
