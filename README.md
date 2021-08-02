# FrontendFromScratch
This repository is to have a place to track and reference my skills, experience and projects with frontend development. If you've found this repository and you're new to Frontend development, my hope would be for it to help you on your journey to understanding Frontend development.

## Table of Contents

* [Understanding the Internet](#Understanding-the-Internet)
  * [Internet Simplified](#Internet-Simplified)
  * [How Websites Work](#How-Websites-Work)
  * [Frontend vs Backend](#Frontend-vs-Backend)
  * [HTML vs CSS vs JavaScript (JS)](#HTML-vs-CSS-vs-JavaScript)
* HTML
* CSS

## Understanding the Internet
### Internet Simplified
#### Definition
Essentially, it's a bunch of devices that are connected to each other so they can communicate with each other. 

Examples: cell phones, computers, tablets, smart tv's, smart refrigerators, Ring doorbell, etc.

Each device is identified by an IP Address. Content, aka data, travels between these devices across the web via documents known as HTTP. 

HTTP is a standarized set of rules, aka a protocol, for how communication should work on the web. 

HTTP stands for Hyper Text Transfer Protocol.

[Back to Table of Contents](#Table-of-Contents)

### How Websites Work
Visit any website of your choice. I'm going to use [Spotify.com](https://spotify.com) for this example.

When you visit the website, click login, scroll to the bottom of the homepage and click [Web Player](https://open.spotify.com/?_ga=2.88727067.1055096665.1627931679-1740594462.1627931679), you are generating what is known as a Request. 

A Request basically says "I want this information", which is known as a resource. The Request will look for the resource on the Spotify web servers and as long as it exists, it will show a Response in the browser.

So, when I visit [Spotify.com](https://spotify.com) in the browser. I'm making a Request that goes out to find the IP address of spotify.com, and then locate the web servers of that IP Address. As long as the IP Address it finds is valid and the request find the web servers, it will look for the homepage of spotify.com and return the Reponse, which is the most recent Spotify web page.

If I visit a link, aka a URL, that doesn't exist on Spotify, the job of the web server would be to return a Response that tells me the web server doesn't know what that is.

For example, if I visit the URL [https://www.spotify.com/us/daphne/](https://www.spotify.com/us/daphne/), I receive a 404 Response.

A 404 Response is a type of HTTP Status Code. 

When a Request is made and the Response returns the correctly expected information, the status code is 200.

You can see a full list of Status Codes referenced in Mozilla's [HTTP response status codes documentation](https://developer.mozilla.org/en-US/docs/Web/HTTP/Status).

[Back to Table of Contents](#Table-of-Contents)

### Frontend vs Backend
If you've been thinking this is a lot of Frontend information to know, you would be correct. 

I think it is important to know how everything works, however, I would like to clarify what is actually going on from the previous [How Websites Work](#How-Websites-Word) example. 

Once I've clarified, I would hope you would be able to distinguish between the Frontend vs the Backend.

When I visited Spotify.com in the browser, and clicked the Web Player URL, these were all part of the Frontend. Any element you can see and interact with on a website or app is known as the Frontend.

Everything that I explained about a Request, Response, web servers, IP Addresses, etc. are things that happen behind the scenes that you don't have to think about as an everyday visitor of a website or app.

Now let me provide another example. 

One of my favorite shooter games is Call of Duty, so I'll use this for an example. In this game, the Frontend would be everything ranging from pressing the start button on the screen, customizing a character, choosing a weapon, selecting a game mode, muting players, walking around in the game, to shooting other players in the game, etc. 

The Backend would be things such as the Requests made when I select a weapon, select a map, shoot a bullet, go prone, etc. 

The Frontend would be visually seeing the Response from the requests. 

So, when I have my character go into the prone position, aka lay down flat on their stomach, a Request is made that likely checks several things I can only take a guess at, such as:

* Is there a prone asset for the character?
* Is the user shooting at the same time they're going prone?
* Are there assets to simulate the user shooting while going into the prone position?

The Response will return the assets aka the visuals (images, video, etc.) in the game, and as a player of the game, I didn't have to think or worry about any of the behind the scenes tasks for Requests, Responses, Web Servers, IP Addresses, etc. 

[Back to Table of Contents](#Table-of-Contents)

### HTML vs CSS vs JavaScript
I like to think about HTML, CSS and JavaScript (JS for short) in this way:

Think about a car, any car and maybe choose your favorite car. 

In the most basic sense, all working cars mostly have the same general features: Body Frame/Shape of the Car, Parts (Engine, Battery, Tires, etc.) and Paint/Color.

So, the car's body frame would be the HTML. You need the shape of the car to have a starting point of the type of car options available. 

For example, if your favorite car is an Aston Martin, you don't want the body frame that's used for a Honda Civic.

The car's parts would be the JavaScript. You don't generally think about these things unless something is going wrong with the car. You also don't have to concern yourself with how to repair parts or know exactly all the parts are located or how they are used in order to learn how to drive. 

So, if you're thinking JavaScript sounds like the Backend, you would be correct. 

Lastly, the car's Paint/Color would be the CSS. Any of the car's colors and graphic designs would be considered CSS in regards to frontend development.

To have a fully functioning and nice looking car, you need the Body Frame, Parts, and Paint/Color. Could a car work without it's CSS? Of course, but having it really does make a difference. 

The same concept applies to a website. You could create a site or an app with just the HTML, but I'd be willing to bet it likely wouldn't be the most useful or exciting website or app created. 

Therefore, to have a fully functioning and nice looking website or app, you should use HTML, CSS and JavaScript together.

[Back to Table of Contents](#Table-of-Contents)

## HTML
* Paragraph Elements
* Headings
* Lists
* Anchor Tags
* Images

[Back to Table of Contents](#Table-of-Contents)

## CSS

[Back to Table of Contents](#Table-of-Contents)
