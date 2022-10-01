# eloisaguanlao.art

Visit http://eloisaguanlao.art


A very basic single page website without using any framework. 

`index.html` defines all the pages and includes a script element with a `route()` function. 
The navigation has links to the same URL with a different anchor.  A listener is registered
on `hashchange` events, and `route()` is invoked with the value of the link anchor.  

Project data is stored in a static json file that occasionally gets edited.  
