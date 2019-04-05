1. Describe the biggest difference between `.forEach` & `.map`.

    The biggest difference is that .forEach changes the array that's passed in, whereas .map returns a new array without mutating the original one.

2. What is the difference between a function and a method?

    A method is a function contained inside an object. So, a function can be used globally, but the method is tied to its object and can only be used with it.

3. What is closure?

    A closure refers to JavaScript's ability for functions to read data declared outside its immediate scope, as long as it's still in its higher context. I think of my code as a series of sideways pyramids, and each part of it has access to anything on one of the wider steps below it. 

4. Describe the four rules of the 'this' keyword.

    1. When used globally, or in a function that's declared globally, 'this' binds to the window/console.
    2. The 'this' keyword binds to the object immediately preceding it when used with a dot. For instance, when used with a method, it will bind to the object the method is inside.
    3. When used with a class or constructor function, 'this' can be used to bind to each new instance of that function/class, allowing you to access the unique data contained within each of them.
    4. The binding of 'this' can be overridden with .call or .apply, to force it to bind to another object. Doing this will allow you to access data inside other objects and manipulate them. 

5. Why do we need super() in an extended class?

    super() binds the class so it inherits the properties and methods from the class you're extending from. 