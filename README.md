# Namaste-React-01-Inception

### Here we will print a simple hello message

```
a. Directly from HTML file
b. Through JS
c. Through React
```

## --------------------ASSIGNMENT--------------------

### 1. What is Emmet?

Emmet is a free add-on for your text editor that allows you to type shortcuts that are then expanded into full pieces of code.

### 2. Difference between a Library and a Framework?

Library is a set of code that was previously written, that can be called upon when building your own code.

Framework is a supporting structure where your own code defines the “meat” of the operations by filling out the structure.

#### Your home is your “Library” :-

There are a less number of rules. You can just throw your T-shirt and place your bag anywhere. You may have to follow some rules but most of them are built by you. You can do it whatever you feel like.

#### Your school is your “Framework” :-

There are a large number of rules . You have your own uniform and your seat is fixed that you cannot place your stuff randomly. You are only allowed to do certain things.

### 3. What is CDN? Why do we use it?

A content delivery network (CDN) refers to a geographically distributed group of servers which work together to provide fast delivery of Internet content.

A CDN allows for the quick transfer of assets needed for loading Internet content including HTML pages, javascript files, stylesheets, images, and videos. The popularity of CDN services continues to grow, and today the majority of web traffic is served through CDNs, including traffic from major sites like Facebook, Netflix, and Amazon.

### 4. Why is React known as React?

React is named React because of its ability to react to changes in data. When the data in a React component changes, React will automatically re-render the component so that it reflects the new data. This makes it easy to create performant user interfaces that always look up-to-date.

### 5. What is crossorigin in script tag?

The HTML script crossorigin Attribute is used for loading an external script into their domain from a third party server or another domain with the support of HTTP CORS Request. This attribute is used to protect sensitive information from the third party when fetching out the results.

### 6. What is the difference between React and ReactDOM?

The reason React and ReactDOM were split into two libraries was due to the arrival of React Native. React contains functionality utilised in web and mobile apps.
ReactDOM functionality is utilised only in web apps.

### 7. What is the difference between react.development.js and react.production.js files via CDN?

The development build is used - as the name suggests - for development reasons. You have Source Maps, debugging and often times hot reloading ability, so rendering development build js files on UI will take a hell of a time as compared to production version which is very crisp, compact, compressed, uglified for better user experience and loading on UI.

### 8. What is async and defer?

async and defer are boolean attributes which are used along the script tags to load the external scripts efficiently into our web page.
When we load a web page, there are two major things happening in our browser
a. HTML parsing
b. Loading of the scripts

Loading of the scripts happens in two parts
a. Fetching the script from the network
b. Actually executing the script line by line

In normal scenario (script tag doesn't contain async or defer keyword), HTML is parsed line by line, and when a script tag is encountered, HTML parsing is paused, script is fetched and executed then and there and then the HTML parsing continues.

In case of async, HTML parsing and script fetching is done in parallel, and the script is executed as soon as it is available blocking the HTML parsing

In case of defer, HTML parsing and script fetching is done in parallel, and the script is executed only after the HTML parsing is done completely.
