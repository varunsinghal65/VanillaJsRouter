# Vanilla JS router

  - The router is very basic and was deveploed for my personal use
  - Its based on the # based routing logic
  - The router is triggered as soon as `hashChange` event is fired
  - It then examines `window.location.href` retrieves the URL after `#` and then tries to determine the requested root by quering its stored routes.
  - The route matching logic is very basic and performs case sensitive string match.
