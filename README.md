# InterviewQuestions

## JavaScript


### What are polyfills in JS?
In JavaScript, polyfills are code snippets or libraries that provide modern functionality to older web browsers that do not support those features natively. They allow developers to use new JavaScript features or APIs in older environments that lack support for them.

Polyfills typically consist of JavaScript code that checks if a certain feature is supported by the browser. If it's not, the polyfill provides an implementation of that feature, enabling the code to run as expected. Polyfills essentially bridge the gap between older browsers and modern web standards.

By using polyfills, developers can write code using the latest JavaScript syntax and APIs without worrying about compatibility issues with older browsers. This approach helps ensure that websites and web applications work consistently across different platforms and browser versions.

There are various polyfill libraries available, such as "core-js," "Babel polyfill," and "polyfill.io," which provide a range of polyfills for different features. Developers can selectively include the required polyfills based on the features they are using in their code.

### How was/is ES6 used on different browsers?

ES6 (ECMAScript 2015) introduced many new features and syntax improvements to JavaScript. However, not all web browsers supported these features initially. To use ES6 features on different browsers, developers employed various techniques. Here are a few common approaches:

#### Transpiling with Babel

One popular technique is to use a tool like Babel. Babel is a JavaScript compiler that can transform ES6 code into backward-compatible versions, usually ES5, which is widely supported across browsers. Transpiling involves converting modern JavaScript syntax into equivalent older syntax to ensure compatibility.

Babel can be integrated into the development workflow using build tools such as webpack or gulp. These tools can automatically transpile the ES6 code into ES5 during the build process, producing a bundle that is compatible with older browsers.

#### Polyfills

In addition to transpiling, developers may also use polyfills to enable ES6 features in older browsers. Polyfills are code snippets or libraries that provide implementations of new features to browsers that lack native support. They fill the gaps in functionality, allowing developers to use ES6 features even in older environments.

Polyfills typically include checks to determine if a feature is supported and provide the implementation if it's not. By including the appropriate polyfills, developers can ensure consistent behavior across different browsers.

#### Feature Detection

Another approach is feature detection. With feature detection, developers check if a particular feature is supported by the browser before using it. This involves using conditional statements or specialized methods to detect the presence of specific ES6 features. If the feature is supported, the ES6 code is executed. Otherwise, fallback code or alternative approaches can be used to achieve similar functionality in older browsers.

By using these techniques, developers can leverage the power of ES6 features in their codebases while still ensuring compatibility with older browsers that may not support those features natively. This allows for a more modern and expressive JavaScript development experience without sacrificing broader browser support.

