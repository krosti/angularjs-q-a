AngularJS Interview's Q&A
=====================

Curated list with some basic **questions** when a FrontEnd-WebUI-JavaScript Developer is interviewee.

### Tests

Test Exam 1: [http://plnkr.co/edit/8C1UgO?p=info](http://plnkr.co/edit/8C1UgO?p=info)

```javascript
    var tags = [angular1.3, directives, $http, formValidation, ngMessages, filters];
  ```


#Questions

1. [Why to use AngularJS?]()
2. What are the advantage of AngularJS?
3. Does AngularJS has dependency on jQuery? 
4. What is jQLite/jQuery Lite? 
5. How to access jQLite? 
6. What browsers AngularJS support? 
7. What is the size of AngularJS file?
8. What are the AngularJS features? 
9. When dependent modules of a module are loaded?
10. What is Angular's prefixes $ and $$?
11. What are Filters in AngularJS? 
12. What are Directives in AngularJS? 
13. What is the role of ng-app, ng-init and ng-model directives? 
14. What are different ways to invoke a directive? 
15. What is restrict option in directive? 
16. Can you define multiple restrict options on a directive?
17. What is auto bootstrap process in AngularJS?
18. What is manual bootstrap process in AngularJS? 
19. What is scope in AngularJS? 
20. What is $scope and $rootScope?
21. What is scope hierarchy?
22. What is the difference between $scope and scope? 
23. How AngularJS is compiled?
24. How AngularJS compilation is different from other JavaScript frameworks?
25. How Directives are compiled?
26. What are Compile, Pre and Post linking in AngularJS?
27. What directives are user to show and hide HTML elements in AngularJS? 
28. Explain directives ng-if, ng-switch and ng-repeat.
29. What are ng-repeat special variables?
30. How AngularJS handle data binding?
31. What is the difference between $watch, $digest and $apply?
32. Explain $watch(), $watchGroup() and $watchCollection() functions on scope.
33. Explain AngularJS scope life-cycle.
34. Explain digest life-cycle in AngularJS.
35. When to use $destroy() function of scope? 
36. What is the difference between $evalAsync and $timeout?
37. What is the difference between $watch and $observe?
38. What is the difference between $parse and $eval?
39. What is Isolate Scope and why it is required?
40. Does AngularJS support MVC?
41. What is Model in AngularJS?
42. What is ViewModel in AngularJS?
43. What is Controller in AngularJS?
44. How to share information between controllers in AngularJS?
45. What is $emit, $broadcast and $on in AngularJS?
46. What is View in AngularJS?
47. What are different AngularJS form properties?
48. What are different states of a form in AngularJS?
49. What is Service in AngularJS?
50. What are different ways to create a service in AngularJS?
51. What is the difference between Factory, Service and Provider?
52. *What is the difference between Kris Kowal's Q and $q?
53. What is Restangular?
54. What are the advantages of Restangular over $resource and $http?
55. What is the difference between $window and ```window``` in AngularJS?
56. What is the difference between $document and ```window.document``` in AngularJS?
57. What is the difference between $timeout and ```window.setTimeout``` in AngularJS?
58. What is the difference between $interval and ```window.setInterval``` in AngularJS?
59. What is Routing in AngularJS?
60. What is AngularUI router and how it is different from ngRoute?
61. What is $injector and $inject?
62. What is Dependency Injection in AngularJS?
63. What is i18n and L10n?
64. What is $locale service?
65. How to manage cookies in AngularJS?
66. How to detect swite event in mobile browsers/devices in AngularJS?
67. How to do animations with AngularJS's helpers?
68. What is the directive that support animations?
69. How to debug AngularJS app in browser?
70. How to securely parse and manipulate your HTML data in AngularJS?
71. What is AngularJS 2.0?
72. What is TypeScript?


----
#Answers

### 1) Why to use AngularJS?

There are following reasons to choose AngularJS as a web development framework:
1. It is based on MVC pattern which helps you to organize your web apps or web application properly.2. It extends HTML by attaching directives to your HTML markup with new attributes or tags and expressionsin order to define very powerful templates.3. It also allows you to create your own directives, making reusable components that fill your needs andabstract your DOM manipulation logic.4. It supports two-way data binding i.e. connects your HTML (views) to your JavaScript objects (models)seamlessly. In this way any change in model will update the view and vice versa without any DOMmanipulation or event handling.5. It encapsulates the behavior of your application in controllers which are instantiated with the help ofdependency injection.6. It supports services that can be injected into your controllers to use some utility code to fullfil your need.For example, it provides $http service to communicate with REST service.7. It supports dependency injection which helps you to test your angular app code very easily.8. Also, AngularJS is mature community to help you. It has widely support over the internet.


### 2) What are the advantage of AngularJS?

There are following advantages of AngularJS:
1. **Data Binding** - AngularJS provides a powerful data binding mechanism to bind data to HTML elements by using scope.2. **Customize & Extensible** - AngularJS is customized and extensible as per you requirement. You can create your own custom components like directives, services etc.3. **Code Reusability** - AngularJS allows you to write code which can be reused. For example custom directive which you can reuse.4. **Support** – AngularJS is mature community to help you. It has widely support over the internet. Also, AngularJS is supported by Google which gives it an advantage.5. **Compatibility** - AngularJS is based on JavaScript which makes it easier to integrate with any other JavaScript library and runnable on browsers like IE, Opera, FF, Safari, Chrome etc.6. **Testing** - AngularJS is designed to be testable so that you can test your AngularJS app components as easy as possible. It has dependency injection at its core, which makes it easy to test.


### 3) Does AngularJS has dependency on jQuery? 

AngularJS has no dependency on jQuery library. But it can be used with jQuery library.


### 4) What is jQLite/jQuery Lite?

jQLite is a subset of jQuery that is built directly into AngularJS. jQLite provides you all the useful features of jQuery. In fact it provides you limited features or functions of jQuery. 
### 5) How to access jQLite? 

jQuery lite or the full jQuery library if available, can be accessed via the AngularJS code by using the element() function in AngularJS. Basically, ```angular.element()``` is an alias for the jQuery function.


### 6) What browsers AngularJS support? 

The latest version of AngularJS 1.3 support Safari, Chrome, Firefox, Opera 15+, IE9+ and mobile browsers(Android, Chrome Mobile, iOS Safari, Opera Mobile).AngularJS 1.3 has dropped support for IE8 but AngularJS 1.2 will continue to support IE8.


### 7) What is the size of AngularJS file?

The size of the compressed and minified file is < 36KB.


### 8) What are the AngularJS features?

The features of AngularJS are listed below:
1. Modules2. Directives3. Templates4. Scope5. Expressions6. Data Binding7. MVC (Model, View & Controller)8. Validations9. Filters10. Services11. Routing12. Dependency Injection13. Testing


### 9) When dependent modules of a module are loaded?

A module might have dependencies on other modules. The dependent modules are loaded by angularbefore the requiring module is loaded.In other words the configuration blocks of the dependent modules execute before the configuration blocks of the requiring module. The same is true for the run blocks. Each module can only be loaded once, even if multiple other modules require it.


### 10) What is Angular’s prefixes $ and $$?

To prevent accidental name collisions with your code, Angular prefixes names of public objects with $ andnames of private objects with $$. So, do not use the $ or $$ prefix in your code.


### 11) What are Filters in AngularJS?

Filters are used to format data before displaying it to the user. They can be used in view templates, controllers, services and directives. There are some built-in filters provided by AngularJS like as Currency, Date, Number, OrderBy, Lowercase, Uppercase etc. You can also create your own filters.

Filter Syntax
```{{ expression | filter}}```


### 12) What are Directives in AngularJS?

AngularJS directives are a combination of AngularJS template markups (HTML attributes or elements, or CSS classes) and supporting JavaScript code. The JavaScript directive code defines the template data and behaviors of the HTML elements.
AngularJS directives are used to extend the HTML vocabulary i.e. they decorate html elements with new behaviors and help to manipulate html elements attributes in interesting way.
There are some built-in directives provided by AngularJS like as ng-app, ng-controller, ng-repeat, ng-model etc.


### 13) What is the role of ng-app, ng-init and ng-model directives?

The main role of these directives is explained as:

- ng-app - Initialize the angular app.- ng-init - Initialize the angular app data.- ng-model - Bind the html elem


### 14) What are different ways to invoke a directive?

There are four methods to invoke a directive in your angular app which are equivalent.| Method          | Syntax |
|-----------------|--------|
| As an attribute |    ```<span my-directive></span>```    |
| As a class      |    ```<span class="my-directive: expression;"></span>```    |
| As an element   |    ```<my-directive></my-directive>```    |
| As a comment    |    ```<!-- directive: my-directive expression -->```    |


--- 
Thanks to many sites in particular to this guys: 
http://www.slideshare.net/proshailendra/angular-js-interview-questions-answers-by-shailendra-chauhan