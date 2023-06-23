# InterviewQuestions

## JavaScript


### What are polyfills in JS?
In JavaScript, polyfills are code snippets or libraries that provide modern functionality to older web browsers that do not support those features natively. They allow developers to use new JavaScript features or APIs in older environments that lack support for them.

Polyfills typically consist of JavaScript code that checks if a certain feature is supported by the browser. If it's not, the polyfill provides an implementation of that feature, enabling the code to run as expected. Polyfills essentially bridge the gap between older browsers and modern web standards.

By using polyfills, developers can write code using the latest JavaScript syntax and APIs without worrying about compatibility issues with older browsers. This approach helps ensure that websites and web applications work consistently across different platforms and browser versions.

There are various polyfill libraries available, such as "core-js," "Babel polyfill," and "polyfill.io," which provide a range of polyfills for different features. Developers can selectively include the required polyfills based on the features they are using in their code.