# Mangipudi Rohit
I am from Hyderabad,India. I completed my undergraduation in Electronics and communication Engineering at Vidya Jyothi Institute of Technology Hyderabad. My hobbies are to play Guitar and Sports. 


[Click here to look at my photo](https://github.com/S554046/assignment2-Mangipudi/blob/main/Image.jpg)

-----
## Countries to visit

In this table i am mentioning the countries that I feel are good to  visit and also the reason why I think that country is worth visiting.

| Country | Reason to visit | Days to spend |
| ------ | ----------------- | ------------ |
| United Kingdom | From the magnificent natural coasts to the heart of the United Kingdom's historical walking tours there and many reasons to visit United Kingdom | 3 months |
| United States of America | America has pretty much everything you might imagine, from theme parks to historical sites, and it is reasonable to say that it is a place unlike any other. | 6 Months |
| India | There are plenty of reasons to visit India, from large festivals to hiking to the top of the world, from rides on trains to taking in traditional dance | 6 months |
| France | The world's top travel destinations include France. A three star hotel in this location is equivalent to a five star hotel elsewhere in the globe. | 3 months |

-----
## Funny Quotes

> "Do not take life too seriously. You will never get out of it alive."
*— Elbert Hubbard* 

> "I just want to lie on the beach and eat hot dogs. That's all I've ever wanted."
*— Kevin Malone, The Office*

-----

## Code Fencing

> How can I replicate a div a certain number of times based on a select-box value? 

<https://stackoverflow.com/questions/6308970/how-can-i-replicate-a-div-a-certain-number-of-times-based-on-a-select-box-value/6309453#6309453>

```
$.fn.duplicate = function(count, cloneEvents) {
       var tmp = [];
       for ( var i = 0; i < count; i++ ) {
               $.merge( tmp, this.clone( cloneEvents ).get() );
       }
       return this.pushStack( tmp );
};
The .clone() function of jQuery will duplicate a set once, but what if you need multiple copies of the same set? You would have to do:

$(elem)
   .clone()
   .appendTo(otherElem)
   .clone()
   .appendTo(otherElem)
   .clone()
   .appendTo(otherElem);
Now you can just:

$(elem)
   .duplicate(n)
   .appendTo(otherElem);

```
link to the code <https://css-tricks.com/snippets/jquery/duplicate-plugin/>
