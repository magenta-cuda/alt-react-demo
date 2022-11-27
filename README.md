# alt-react-demo

**This is a port of sv-rr to the Bootstrap toolkit.**

This a re-implementation of [sv-rr](https://github.com/magenta-cuda/sv-rr) (which is a React/Redux application) using only native Javascript. I have thought for some time that the ideas of React and Redux are quite simple and that for smaller less complex applications these ideas could be implemented directly in Javascript without using a heavy framework. This is my first attempt at implementing the ideas of React and Redux directly in Javascript. I actually also use jQuery (because I am much more fluent in jQuery than ES6) and Bootstrap for CSS.

There are some very significant advantages to a bespoke application versus an application built using a framework.

+Since a framework must support many different kinds of applications it will contain code to handle many different cases that will not occur in your application. So a bespoke application will be much smaller and much lighter without this unnecessary bloat.

+Further, there will be conditions that will be true in your application that will not be true in other applications. These conditions will allow you to greatly simplify and greatly optimize your code. So a bespoke application will much easier to understand and also much execute much faster.

+A bespoke application will be much closer to the metal. Since you wrote everything you will have direct access to all the Javascript code and all the Javascript objects. A bespoke application is much easier to understand and much easier to debug since everything is visible.
