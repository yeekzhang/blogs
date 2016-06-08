Title: JavaScript Ecosystem
Date: 2016-05-25 10:48
Category: Ecosystem JavaScript

# [SigmaJS](http://sigmajs.org/)
Sigma is a JavaScript library dedicated to graph drawing. It makes easy to publish networks on Web pages, and allows developers to integrate network exploration in rich Web applications.

# [MooTools](http://mootools.net/)
MooTools is a collection of JavaScript utilities designed for the intermediate to advanced JavaScript developer. It allows you to write powerful and flexible code with its elegant, well documented, and coherent APIs.

MooTools code is extensively documented and easy to read, enabling you to extend the functionality to match your requirements.

# [Electron](http://electron.atom.io/)
Build cross platform desktop apps with JavaScript, HTML, and CSS.

# [Marked](https://github.com/chjj/marked)
A markdown parser and compiler. Built for speed.

# [node-serialport](https://github.com/EmergingTechnologyAdvisors/node-serialport)
Node.js package to access serial ports for reading and writing OR Welcome your robotic JavaScript overlords. Better yet, program them!

# [Redux](https://github.com/reactjs/redux)
[Reference](http://www.codeproject.com/Articles/1103559/How-Redux-works)
[Redux](http://redux.js.org/) is a recent Javascript library (started in May 2015) which is described as “predictable state container for JavaScript apps”. It takes the idea from Flux architecture and simplifies it, reduces a lot of boiler plate code required by Flux architecture itself. Despite its small code size, it quickly becomes one of the most popular library used together with ReactJS (at the time of writing this article, its github repository has more than 18000 stars and 800 watch).

For beginners to Redux/Flux architecture, it seems quite intimidating at first since it introduces quite a number of new terminologies and requires us to approach application design in a different way than other Javascript frameworks like AngularJS. If you use Redux with ReactJS, you will need to use another library, React Redux, to glue these two libraries together, which makes the learning process even more challenging. Although there are already a lot of articles online describing Redux/ReactJS and how to use them together, I still find it helpful to understand how Redux/React Redux work internally. In this article, I’ll guide you through the source code of Redux/React Redux and see how the libraries are implemented. Fortunately, both libraries are relatively small in size and we can easily cover their concepts in the scope of this article.