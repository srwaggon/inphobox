InPhOboxes
==============

This repository contains the starter code for creating an InPhObox. This project
is designed to be a creative programming task to see how well you will be able
to integrate with the InPhO Project development given some skeleton code and
documentation. 

You will be working with a HTML file that imports three libraries used
throughout the InPhO Project: jQuery, Mustache.js, and Bootstrap. jQuery is a
general purpose JavaScript library used primarily for API calls and client-side
behavior. Mustache.js is a client-side templating engine used to display data
stored in JSON format. Bootstrap is a CSS framework used to make websites
pretty. All three libraries are ubiquitous in web development, and have very
large userbases, making them easy to find help using Google and StackOverflow.

Creating a basic InPhObox should take fewer than 5 hours, even with no web
development experience. We are largely looking at your ability for
self-instruction and

The Task
-----------
Create an InPhObox similar to the infoboxes displayed alongside [Google search
results](https://www.google.com/search?q=plato) or [Wikipedia
entries](http://en.wikipedia.org/wiki/Plato). To do this, you will need to query
the InPhO JSON API to return data from our database using the [jQuery
library](http://jquery.com/) and display it on a web page using the [Mustache 
templating engine](http://mustache.github.io/). We request that you do this
using the [Plato InPhO entry](https://inpho.cogs.indiana.edu/thinker/3724).

1.  Download the starter files as a zip archive.
2.  Using the [jQuery.getJSON()](http://api.jquery.com/jQuery.getJSON/)
function, query the InPhO API for the Plato entry at 
[https://inpho.cogs.indiana.edu/thinker/3724.json].
3.  Take the data and render it to the page using 
[mustache.js](http://mustache.github.io/mustache.5.html).
4.  To make the data presentable, use [Bootstrap 2.3.2](http://getbootstrap.com/2.3.2/index.html).

Tips
------
To help with developing your template, you can use the [mustache.js demo
page](http://mustache.github.io/#demo), replacing the template with your
template and the JSON data with the data from the API call.

To help making the information more presentable, the
[Bootstrap 2.3.2 documentation](http://getbootstrap.com/2.3.2/)
has many examples that will help you.

Benchmarks
------------
1.  Able to display data based on the Plato InPhO record.
2.  Able to display data from an arbitrary InPhO thinker record. 
(Display has been encapsulated into a single callable function).
3.  Able to display data from multiple sources (i.e., InPhO and dbpedia).

Resources
-----------
*   [jQuery Documentation](http://api.jquery.com/)
*   [Mustache.js Documentation](http://mustache.github.io/mustache.5.html)
*   [Bootstrap 2.3.2 Documentation](http://getbootstrap.com/2.3.2/)
*   [Mustache.js JavaScript Implementation](https://github.com/janl/mustache.js)
*   [CSS Tutorial](http://learn.shayhowe.com/html-css/)

