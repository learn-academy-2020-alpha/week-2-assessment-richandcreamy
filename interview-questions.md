# ASSESSMENT 2: Interview Practice Questions

Answer the following questions. First, without external resources. Challenge yourself to answer from memory. Then, research the question to expand on your answer. Even if you feel you have answered the question completely on your own, there is always something more to learn.

1. What does CRUD stand for?

  Your answer:
  
  Create Read Update Delete

The web's action verbs and the minimal amount of interaction a website or application needs to be considered fully featured. Also what you can expect to be asble to do with RESTful APIs.

  Researched answer:

In computer programming, create, read, update, and delete[1] (CRUD) are the four basic functions of persistent storage. The comparison of the database oriented CRUD operations to the HTTP methods has some flaws. Strictly speaking, both PUT and POST can create and update resources; the key difference is that contrary to POST, PUT is idempotent, meaning that multiple identical requests should have the same effect as a single request. Consequently PUT is a "replace" operation, which one could argue is not "update".

2. What are the 5 HTTP verbs?

  Your answer: Read, Put, Post, Update, Patch 

I realize I have confused these terms and thought they were interchangeable.

  Researched answer:

GET
The GET method requests a representation of the specified resource. Requests using GET should only retrieve data and should have no other effect. \

HEAD
The HEAD method asks for a response identical to that of a GET request, but without the response body. This is useful for retrieving meta-information written in response headers, without having to transport the entire content.

POST
The POST method requests that the server accept the entity enclosed in the request as a new subordinate of the web resource identified by the URI. 

PUT
The PUT method requests that the enclosed entity be stored under the supplied URI. 

DELETE
The DELETE method deletes the specified resource.

TRACE
The TRACE method echoes the received request so that a client can see what (if any) changes or additions have been made by intermediate servers.

OPTIONS
The OPTIONS method returns the HTTP methods that the server supports for the specified URL.

CONNECT
The CONNECT method converts the request connection to a transparent TCP/IP tunnel, usually to facilitate SSL-encrypted communication (HTTPS) through an unencrypted HTTP proxy.

PATCH
The PATCH method applies partial modifications to a resource.


3. When creating a basic (stateless) class component in React, what are the necessary elements needed to render "Hello World" on the page?

  Your answer:
You'll need to call the React script from either from the server hosting the React or self hosting it. Then instruct the React component to inherit the characteristics it needs to do be able to do work. The text is placed within a render that is in a master div. 

  Researched answer:
A React stateless components simply returns a value which you input in your view. There are no states but methods may be there. It is very easy to create maintainable and readable code. The stateless component will break the components into small parts and pass data through props. This is also called as Pure Function. There is no ‘this’ keyword there. And it also has no lifecycle method like componentDidMount.

The stateless component takes props as an argument and returns a new react component. When rendering stateless component you need to just call your stateless component function and pass props.


4. What is JSX?

  Your answer:
The combination of Javascript and HTML code useable in react. It is closer to XML than HTML.

  Researched answer: https://illustrated.dev/jsx/ I really like this illustrated explanation. 
JSX stands for JavaScript XML. With React, it's an extension for XML-like code for elements and components. JSX is a XML-like syntax extension to ECMAScript without any defined semantics. JSX is a preprocessor step that adds XML syntax to JavaScript. You can definitely use React without JSX but JSX makes React a lot more elegant.Just like XML, JSX tags have a tag name, attributes, and children. If an attribute value is enclosed in quotes, the value is a string. Otherwise, wrap the value in braces and the value is the enclosed JavaScript expression.

5. What is the difference between React state and props?

Your answer: State is a dynamic value. Props is a set property.

Researched answer: The main difference between state and props is that props are immutable. This is why the container component should define the state that can be updated and changed, while the child components should only pass data from the state using props.


6. STRETCH: What is hoisting in JavaScript?

Your answer: Bringing in data from a child component into the parent.

Researched answer: Hoisting is a behavior in JavaScript where variable and function declarations are “hoisted” to the top of their scope before code execution. This can result in confusing behavior, such as the ability to call variables and functions before you wrote them.



## Looking Ahead: Terms for Next Week

Research and define the following terms to the best of your ability.
// I didn't know this needed to be researched last assessment and tried to guess last week's terms.

- React lifecycle methods

Each component in React has a lifecycle which you can monitor and manipulate during its three main phases. The three phases are: Mounting, Updating, and Unmounting. This reinds me of working with disk drives except with he DOM instead of physical media.

- API

An application program interface (API) is code that allows two software programs to communicate with each other. An API defines the correct way for a developer to request services from an operating system (OS) or other application and expose data within different contexts and across multiple channels.

- event.preventDefault()

The Event interface's preventDefault() method tells the user agent that if the event does not get explicitly handled, its default action should not be taken as it normally would be. The event continues to propagate as usual, unless one of its event listeners calls stopPropagation() or stopImmediatePropagation(), either of which terminates propagation at once.

- DOM events

DOM Events are sent to notify code of interesting things that have taken place. Each event is represented by an object which is based on the Event interface, and may have additional custom fields and/or functions used to get additional information about what happened. Events can represent everything from basic user interactions to automated notifications of things happening in the rendering model.