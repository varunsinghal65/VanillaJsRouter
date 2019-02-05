# Vanilla JS super simple router 

## Overview

  - The router is very basic and was deveploed for my personal use
  - Its based on the # based routing logic
  - The router is triggered as soon as `hashChange` event is fired
  - It then examines `window.location.href` retrieves the URL after `#` and then tries to determine the requested route by quering its stored routes.
  - The route matching logic is very basic and performs case sensitive string match.

## Features 

- The router intercepts the URL changes and then transfers constrol
to a callback function depending upon the URL intercepted

### Adding a route in 2 lines

Add the following code :

#### In your js

``
router.addRoute(new Route("r1", route1CallBack, scopeObj));
``

#### In your html

Create the following anchor tag :

``
<a href="#r1">Route 1</a>
``

That's it !!!

Congrats ! routing setup complete

