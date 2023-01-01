# 🖲 39 TypeScript interview questions for web developers in 2023

TypeScript is a must know if you're a front developer or even a fullstack developer. Our curated list of TypeScript questions can be used for all levels of developers. Go through all questions and nail your next web developer tech interview in 2021.

</br>

<p align="center">
  <a href="https://devinterview.io/">
  <img src="https://source.unsplash.com/collection/52661698/600x300">
  </a>
</p>

</br>

> You can also find all 39 answers here 👉🏼 https://devinterview.io/dev/typescript-interview-questions

</br>

<div data-v-4865b274="" data-v-43a77f0d=""><div data-v-4865b274=""><h2 data-v-4865b274="">🔹 1. What is Typescript and why one should use it?</h2></div> <div data-v-4865b274=""><h3 data-v-4865b274="">Answer:</h3> <div data-v-4865b274=""><div><div><div class="AnswerBody"><p>TypeScript is a free and open-source programming language developed and maintained by Microsoft. It is a strict syntactical superset of JavaScript, and adds optional static typing and class-based object-oriented programming to the language.</p></div></div><div class="row my-2"><div><span><i>Source:</i>&nbsp;<span><a href="https://stackoverflow.com/" rel="noreferrer" target="_blank" title=" What is Typescript and why one should use it? Interview Questions Source To Answer">Stackoverflow.com</a></span></span>&nbsp; &nbsp;</div></div></div></div></div> <br data-v-4865b274=""><br data-v-4865b274=""></div><div data-v-4865b274="" data-v-43a77f0d=""><div data-v-4865b274=""><h2 data-v-4865b274="">🔹 2. What are the benefits of TypeScript?</h2></div> <div data-v-4865b274=""><h3 data-v-4865b274="">Answer:</h3> <div data-v-4865b274=""><div><div><div class="AnswerBody"><p>TypeScript has following benefits.</p><ul><li>It helps in code structuring.</li><li>Use class based object oriented programming.</li><li>Impose coding guidelines.</li><li>Offers type checking.</li><li>Compile time error checking.</li><li>Intellisense.</li></ul></div></div><div class="row my-2"><div><span><i>Source:</i>&nbsp;<span><a href="http://www.talkingdotnet.com/typescript-interview-questions/" rel="noreferrer" target="_blank" title="What are the benefits of TypeScript? Interview Questions Source To Answer">talkingdotnet.com</a></span></span>&nbsp; &nbsp;</div></div></div></div></div> <br data-v-4865b274=""><br data-v-4865b274=""></div><div data-v-4865b274="" data-v-43a77f0d=""><div data-v-4865b274=""><h2 data-v-4865b274="">🔹 3. What is TypeScript and why would I use it in place of JavaScript?</h2></div> <div data-v-4865b274=""><h3 data-v-4865b274="">Answer:</h3> <div data-v-4865b274=""><div><div><div class="AnswerBody"><p><strong>TypeScript</strong> is a superset of JavaScript which primarily provides optional static typing, classes and interfaces. One of the big benefits is to enable IDEs to provide a richer environment for spotting common errors as <em>you type the code</em>. For a large JavaScript project, adopting TypeScript might result in more robust software, while still being deployable where a regular JavaScript application would run.</p><p>In details:</p><ul><li>TypeScript supports new ECMAScript standards and compiles them to (older) ECMAScript targets of your choosing. This means that you can use features of ES2015 and beyond, like modules, lambda functions, classes, the spread operator, destructuring, today. </li><li>JavaScript code is valid TypeScript code; TypeScript is a superset of JavaScript. </li><li>TypeScript adds type support to JavaScript. The type system of TypeScript is relatively rich and includes: interfaces, enums, hybrid types, generics, union and intersection types, access modifiers and much more. TypeScript makes typing a bit easier and a lot less explicit by the usage of type inference.</li><li>The development experience with TypeScript is a great improvement over JavaScript. The IDE is informed in real-time by the TypeScript compiler on its rich type information. </li><li>With strict null checks enabled (<code>--strictNullChecks</code> compiler flag) the TypeScript compiler will not allow undefined to be assigned to a variable unless you explicitly declare it to be of nullable type. </li><li>To use TypeScript you need a build process to compile to JavaScript code. The TypeScript compiler can inline source map information in the generated .js files or create separate .map files. This makes it possible for you to set breakpoints and inspect variables during runtime directly on your TypeScript code. </li><li>TypeScript is open source (Apache 2 licensed, see github) and backed by Microsoft. <em>Anders Hejlsberg</em>, the lead architect of C# is spearheading the project.</li></ul></div></div><div class="row my-2"><div><span><i>Source:</i>&nbsp;<span><a href="https://stackoverflow.com/questions/12694530/what-is-typescript-and-why-would-i-use-it-in-place-of-javascript" rel="noreferrer" target="_blank" title="What is TypeScript and why would I use it in place of JavaScript? Interview Questions Source To Answer">stackoverflow.com</a></span></span>&nbsp; &nbsp;</div></div></div></div></div> <br data-v-4865b274=""><br data-v-4865b274=""></div><div data-v-4865b274="" data-v-43a77f0d=""><div data-v-4865b274=""><h2 data-v-4865b274="">🔹 4. Explain generics in TypeScript</h2></div> <div data-v-4865b274=""><h3 data-v-4865b274="">Answer:</h3> <div data-v-4865b274=""><div><div><div class="AnswerBody"><p>Generics are able to create a component or function to work over a variety of types rather than a single one.</p><pre><code><span class="token cComment">/** A class definition with a generic parameter */</span>
<span class="token cVar">class</span> <span class="token class-name">Queue</span><span class="token cBase">&lt;</span><span class="token cMod">T</span><span class="token cBase">&gt;</span> <span class="token cBase">{</span>
  <span class="token cVar">private</span> data <span class="token cBase">=</span> <span class="token cBase">[</span><span class="token cBase">]</span><span class="token cBase">;</span>
  <span class="token function-variable cMod">push</span> <span class="token cBase">=</span> <span class="token cBase">(</span><span class="token parameter">item<span class="token cBase">:</span> <span class="token cMod">T</span></span><span class="token cBase">)</span> <span class="token cBase">=&gt;</span> <span class="token cVar">this</span><span class="token cBase">.</span>data<span class="token cBase">.</span><span class="token cMod">push</span><span class="token cBase">(</span>item<span class="token cBase">)</span><span class="token cBase">;</span>
  pop <span class="token cBase">=</span> <span class="token cBase">(</span><span class="token cBase">)</span><span class="token cBase">:</span> <span class="token parameter"><span class="token cMod">T</span></span> <span class="token cBase">=&gt;</span> <span class="token cVar">this</span><span class="token cBase">.</span>data<span class="token cBase">.</span><span class="token cMod">shift</span><span class="token cBase">(</span><span class="token cBase">)</span><span class="token cBase">;</span>
<span class="token cBase">}</span>

<span class="token cVar">const</span> queue <span class="token cBase">=</span> <span class="token cVar">new</span> <span class="token class-name">Queue</span><span class="token cBase">&lt;</span>number<span class="token cBase">&gt;</span><span class="token cBase">(</span><span class="token cBase">)</span><span class="token cBase">;</span>
queue<span class="token cBase">.</span><span class="token cMod">push</span><span class="token cBase">(</span><span class="token cNum">0</span><span class="token cBase">)</span><span class="token cBase">;</span>
queue<span class="token cBase">.</span><span class="token cMod">push</span><span class="token cBase">(</span><span class="token cString">"1"</span><span class="token cBase">)</span><span class="token cBase">;</span> <span class="token cComment">// ERROR : cannot push a string. Only numbers allowed</span></code></pre></div></div><div class="row my-2"><div><span><i>Source:</i>&nbsp;<span><a href="https://basarat.gitbooks.io/typescript/docs/types/generics.html" rel="noreferrer" target="_blank" title="Explain generics in TypeScript Interview Questions Source To Answer">basarat.gitbooks.io</a></span></span>&nbsp; &nbsp;</div></div></div></div></div> <br data-v-4865b274=""><br data-v-4865b274=""></div><div data-v-4865b274="" data-v-43a77f0d=""><div data-v-4865b274=""><h2 data-v-4865b274="">🔹 5. What are Modules in Typescript?</h2></div> <div data-v-4865b274=""><h3 data-v-4865b274="">Answer:</h3> <div data-v-4865b274=""><div><div><div class="AnswerBody"><p>Modules in Typescript helps in organizing the code. There are 2 types of Modules — Internal and External</p><ul><li><p><strong>Internal Modules</strong> are now replaceable by using Typescript’s namespace.</p></li><li><p><strong>External Modules</strong> used to specify and load dependencies between multiple external js files. If there is only one js file used, then external modules are not relevant.</p></li></ul></div></div><div class="row my-2"><div><span><i>Source:</i>&nbsp;<span><a href="https://stackoverflow.com/" rel="noreferrer" target="_blank" title="What are Modules in Typescript? Interview Questions Source To Answer">Stackoverflow.com</a></span></span>&nbsp; &nbsp;</div></div></div></div></div> <br data-v-4865b274=""><br data-v-4865b274=""></div><div data-v-4865b274="" data-v-43a77f0d=""><div data-v-4865b274=""><h2 data-v-4865b274="">🔹 6. List the built-in types in Typescript</h2></div> <div data-v-4865b274=""><h3 data-v-4865b274="">Answer:</h3> <div data-v-4865b274=""><div><div><div class="AnswerBody"><p>These are also called the primitive types in TypeScript:</p><ul><li><strong>Number</strong> type: it is used to represent number type values and represents double precision floating point values.</li></ul><pre><code><span class="token cVar">var</span> variable_name<span class="token cBase">:</span> number<span class="token cBase">;</span></code></pre><ul><li><strong>String</strong> type: it represents a sequence of characters stored as Unicode UTF-16 code. It is the same as JavaScript primitive type.</li></ul><pre><code><span class="token cVar">var</span> variable_name<span class="token cBase">:</span> string<span class="token cBase">;</span></code></pre><ul><li><strong>Boolean</strong> type: in Typescript, it is used to represent a logical value. When we use the Boolean type, we get output only in true or false. It is also the same as JavaScript primitive type.</li></ul><pre><code><span class="token cVar">var</span> variable_name<span class="token cBase">:</span> bool<span class="token cBase">;</span></code></pre><ul><li><strong>Null</strong> type: it represents a null literal and it is not possible to directly reference the null type value itself.</li></ul><pre><code><span class="token cVar">var</span> variable_name<span class="token cBase">:</span>number <span class="token cBase">=</span> <span class="token cVar">null</span><span class="token cBase">;</span></code></pre><ul><li><strong>Undefined</strong> type: it is the type of undefined literal. This type of built-in type is the sub-type of all the types.</li></ul><pre><code><span class="token cVar">var</span> variable_name<span class="token cBase">:</span>number <span class="token cBase">=</span> <span class="token cVar">undefined</span><span class="token cBase">;</span></code></pre></div></div><div class="row my-2"><div><span><i>Source:</i>&nbsp;<span><a href="https://stackoverflow.com/" rel="noreferrer" target="_blank" title="List the built-in types in Typescript Interview Questions Source To Answer">Stackoverflow.com</a></span></span>&nbsp; &nbsp;</div></div></div></div></div> <br data-v-4865b274=""><br data-v-4865b274=""></div><div data-v-4865b274="" data-v-43a77f0d=""><div data-v-4865b274=""><h2 data-v-4865b274="">🔹 7. How to call base class constructor from child class in TypeScript?</h2></div> <div data-v-4865b274=""><h3 data-v-4865b274="">Answer:</h3> <div data-v-4865b274=""><div><div><div class="AnswerBody"><p>We can call base class constructor using <code>super()</code>.</p></div></div><div class="row my-2"><div><span><i>Source:</i>&nbsp;<span><a href="http://www.talkingdotnet.com/typescript-interview-questions/" rel="noreferrer" target="_blank" title="How to call base class constructor from child class in TypeScript? Interview Questions Source To Answer">http://www.talkingdotnet.com</a></span></span>&nbsp; &nbsp;</div></div></div></div></div> <br data-v-4865b274=""><br data-v-4865b274=""></div><div data-v-4865b274="" data-v-43a77f0d=""><div data-v-4865b274=""><h2 data-v-4865b274="">🔹 8. Do we need to compile TypeScript files and why?</h2></div> <div data-v-4865b274=""><h3 data-v-4865b274="">Answer:</h3> <div data-v-4865b274=""><div><div><div class="AnswerBody"><p>Yes we do. Typescript is just a language Extension browsers can't interpret it. Converting from TypeScript to JavaScript is called compiling. Compiling doesn't mean binary code is created in this case. For this kind of translation, also the term transpilation is used instead of compilation.</p></div></div><div class="row my-2"><div><span><i>Source:</i>&nbsp;<span><a href="https://stackoverflow.com/questions/45125284/why-is-angular-compiled" rel="noreferrer" target="_blank" title="Do we need to compile TypeScript files and why? Interview Questions Source To Answer">stackoverflow.com</a></span></span>&nbsp; &nbsp;</div></div></div></div></div> <br data-v-4865b274=""><br data-v-4865b274=""></div><div data-v-4865b274="" data-v-43a77f0d=""><div data-v-4865b274=""><h2 data-v-4865b274="">🔹 9. What is TypeScript and why do we need it?</h2></div> <div data-v-4865b274=""><h3 data-v-4865b274="">Answer:</h3> <div data-v-4865b274=""><div><div><div class="AnswerBody"><p>JavaScript is the only client side language universally supported by all browsers. But JavaScript is not the best designed language. It’s not a class-based object-oriented language, doesn’t support class based inheritance, unreliable dynamic typing and lacks in compile time error checking. And TypeScript addresses all these problems. In other words, TypeScript is an attempt to “fix” JavaScript problems.</p><p>TypeScript is a free and open source programming language developed and maintained by Microsoft. It is a strict superset of JavaScript, and adds <strong>optional static typing</strong> and <strong>class-based object-oriented programming</strong> to the language. TypeScript is quite easy to learn and use for developers familiar with C#, Java and all strong typed languages. At the end of day “TypeScript is a language that generates plain JavaScript files.”</p><p>As stated on <a href="http://www.typescriptlang.org/">Typescript official website</a>, “TypeScript lets you write JavaScript the way you really want to. TypeScript is a typed superset of JavaScript that compiles to plain JavaScript. Any browser. Any host. Any OS. Open Source.” Where “<strong>typed</strong>” means that it considers the types of variables, parameters and functions.</p></div></div><div class="row my-2"><div><span><i>Source:</i>&nbsp;<span><a href="http://www.talkingdotnet.com/typescript-interview-questions/" rel="noreferrer" target="_blank" title="What is TypeScript and why do we need it? Interview Questions Source To Answer">talkingdotnet.com</a></span></span>&nbsp; &nbsp;</div></div></div></div></div> <br data-v-4865b274=""><br data-v-4865b274=""></div><div data-v-4865b274="" data-v-43a77f0d=""><div data-v-4865b274=""><h2 data-v-4865b274="">🔹 10. What is "Decorators" in TypeScript?</h2></div> <div data-v-4865b274=""><h3 data-v-4865b274="">Answer:</h3> <div data-v-4865b274=""><div><div><div class="AnswerBody"><p>A <em>Decorator</em> is a special kind of declaration that can be attached to a class declaration, method, accessor, property, or parameter. Decorators are functions that take their target as the argument. With decorators we can run arbitrary code around the target execution or even entirely replace the target with a new definition.</p><p>There are 4 things we can decorate in ECMAScript2016 (and Typescript): constructors, methods, properties and parameters. </p></div></div><div class="row my-2"><div><span><i>Source:</i>&nbsp;<span><a href="https://www.sparkbit.pl/typescript-decorators/" rel="noreferrer" target="_blank" title="What is &quot;Decorators&quot; in TypeScript? Interview Questions Source To Answer">www.sparkbit.pl</a></span></span>&nbsp; &nbsp;</div></div></div></div></div> <br data-v-4865b274=""><br data-v-4865b274=""></div><div data-v-4865b274="" data-v-43a77f0d=""><div data-v-4865b274=""><h2 data-v-4865b274="">🔹 11. What is Interface in TypeScript?</h2></div> <div data-v-4865b274=""><h3 data-v-4865b274="">Answer:</h3> <div data-v-4865b274=""><div><div><div class="AnswerBody"><p>One of TypeScript’s core principles is that type-checking focuses on the <em>shape</em> that values have.</p><p>An <code>interface</code> is a virtual structure that only exists within the context of TypeScript. The TypeScript compiler uses interfaces solely for type-checking purposes.</p><p>When you define your interface you’re saying that any object (not an instance of a class) given this contract must be an object containing interfaces properties.</p></div></div><div class="row my-2"><div><span><i>Source:</i>&nbsp;<span><a href="https://medium.com/front-end-hacking/typescript-class-vs-interface-99c0ae1c2136" rel="noreferrer" target="_blank" title="What is Interface in TypeScript? Interview Questions Source To Answer">medium.com</a></span></span>&nbsp; &nbsp;</div></div></div></div></div> <br data-v-4865b274=""><br data-v-4865b274=""></div><div data-v-4865b274="" data-v-43a77f0d=""><div data-v-4865b274=""><h2 data-v-4865b274="">🔹 12. What is the difference between Classes and Interfaces in Typescript?</h2></div> <div data-v-4865b274=""><h3 data-v-4865b274="">Answer:</h3> <div data-v-4865b274=""><div><div><div class="AnswerBody"><p>We use classes as object factories. A class defines a blueprint of what an object should look like and act like and then implements that blueprint by initialising class properties and defining methods. Classes are present throughout all the phases of our code.</p><p>Unlike classes, an interface is a virtual structure that only exists within the context of TypeScript. The TypeScript compiler uses interfaces solely for type-checking purposes. Once code is transpiled to its target language, it will be stripped from interfaces.</p><p>A class may define a factory or a singleton by providing initialisation to its properties and implementation to its methods, an interface is simply a structural contract that defines what the properties of an object should have as a name and as a type.</p></div></div><div class="row my-2"><div><span><i>Source:</i>&nbsp;<span><a href="https://toddmotto.com/classes-vs-interfaces-in-typescript" rel="noreferrer" target="_blank" title="What is the difference between Classes and Interfaces in Typescript? Interview Questions Source To Answer">toddmotto.com</a></span></span>&nbsp; &nbsp;</div></div></div></div></div> <br data-v-4865b274=""><br data-v-4865b274=""></div><div data-v-4865b274="" data-v-43a77f0d=""><div data-v-4865b274=""><h2 data-v-4865b274="">🔹 13. How to implement class constants in TypeScript?</h2></div> <div data-v-4865b274=""><h3 data-v-4865b274="">Answer:</h3> <div data-v-4865b274=""><div><div><div class="AnswerBody"><p>In TypeScript, the <code>const</code> keyword cannot be used to declare class properties. Doing so causes the compiler to an error with "A class member cannot have the 'const' keyword." TypeScript 2.0 has the <code>readonly</code> modifier:</p><pre><code><span class="token cVar">class</span> <span class="token class-name">MyClass</span> <span class="token cBase">{</span>
    readonly myReadonlyProperty <span class="token cBase">=</span> <span class="token cNum">1</span><span class="token cBase">;</span>

    <span class="token cMod">myMethod</span><span class="token cBase">(</span><span class="token cBase">)</span> <span class="token cBase">{</span>
        console<span class="token cBase">.</span><span class="token cMod">log</span><span class="token cBase">(</span><span class="token cVar">this</span><span class="token cBase">.</span>myReadonlyProperty<span class="token cBase">)</span><span class="token cBase">;</span>
    <span class="token cBase">}</span>
<span class="token cBase">}</span>

<span class="token cVar">new</span> <span class="token class-name">MyClass</span><span class="token cBase">(</span><span class="token cBase">)</span><span class="token cBase">.</span>myReadonlyProperty <span class="token cBase">=</span> <span class="token cNum">5</span><span class="token cBase">;</span> <span class="token cComment">// error, readonly</span></code></pre></div></div><div class="row my-2"><div><span><i>Source:</i>&nbsp;<span><a href="https://stackoverflow.com/questions/37265275/how-to-implement-class-constants-in-typescript" rel="noreferrer" target="_blank" title="How to implement class constants in TypeScript? Interview Questions Source To Answer">stackoverflow.com</a></span></span>&nbsp; &nbsp;</div></div></div></div></div> <br data-v-4865b274=""><br data-v-4865b274=""></div><div data-v-4865b274="" data-v-43a77f0d=""><div data-v-4865b274=""><h2 data-v-4865b274="">🔹 14. What is getters/setters in TypeScript?</h2></div> <div data-v-4865b274=""><h3 data-v-4865b274="">Answer:</h3> <div data-v-4865b274=""><div><div><div class="AnswerBody"><p>TypeScript supports <strong>getters/setters</strong> as a way of intercepting accesses to a member of an object. This gives you a way of having finer-grained control over how a member is accessed on each object.</p><pre><code><span class="token cVar">class</span> <span class="token class-name">foo</span> <span class="token cBase">{</span>
  <span class="token cVar">private</span> _bar<span class="token cBase">:</span>boolean <span class="token cBase">=</span> <span class="token cBool">false</span><span class="token cBase">;</span>

  <span class="token cVar">get</span> <span class="token cMod">bar</span><span class="token cBase">(</span><span class="token cBase">)</span><span class="token cBase">:</span>boolean <span class="token cBase">{</span>
    <span class="token cVar">return</span> <span class="token cVar">this</span><span class="token cBase">.</span>_bar<span class="token cBase">;</span>
  <span class="token cBase">}</span>
  <span class="token cVar">set</span> <span class="token cMod">bar</span><span class="token cBase">(</span><span class="token parameter">theBar<span class="token cBase">:</span>boolean</span><span class="token cBase">)</span> <span class="token cBase">{</span>
    <span class="token cVar">this</span><span class="token cBase">.</span>_bar <span class="token cBase">=</span> theBar<span class="token cBase">;</span>
  <span class="token cBase">}</span>
<span class="token cBase">}</span>

<span class="token cVar">var</span> myBar <span class="token cBase">=</span> myFoo<span class="token cBase">.</span>bar<span class="token cBase">;</span>  <span class="token cComment">// correct (get)</span>
myFoo<span class="token cBase">.</span>bar <span class="token cBase">=</span> <span class="token cBool">true</span><span class="token cBase">;</span>  <span class="token cComment">// correct (set)</span></code></pre></div></div><div class="row my-2"><div><span><i>Source:</i>&nbsp;<span><a href="http://www.typescriptlang.org/docs/handbook/classes.html" rel="noreferrer" target="_blank" title="What is getters/setters in TypeScript? Interview Questions Source To Answer">typescriptlang.org</a></span></span>&nbsp; &nbsp;</div></div></div></div></div> <br data-v-4865b274=""><br data-v-4865b274=""></div><div data-v-4865b274="" data-v-43a77f0d=""><div data-v-4865b274=""><h2 data-v-4865b274="">🔹 15. Does TypeScript support all object oriented principles?</h2></div> <div data-v-4865b274=""><h3 data-v-4865b274="">Answer:</h3> <div data-v-4865b274=""><div><div><div class="AnswerBody"><p>The answer is <strong>YES</strong>. There are 4 main principles to Object Oriented Programming: </p><ul><li>Encapsulation, </li><li>Inheritance, </li><li>Abstraction, and </li><li>Polymorphism. </li></ul><p>TypeScript can implement all four of them with its smaller and cleaner syntax.</p></div></div><div class="row my-2"><div><span><i>Source:</i>&nbsp;<span><a href="https://jonathanmh.com/typescript-node-js-tutorial-backend-beginner/" rel="noreferrer" target="_blank" title="Does TypeScript support all object oriented principles? Interview Questions Source To Answer">jonathanmh.com</a></span></span>&nbsp; &nbsp;</div></div></div></div></div> <br data-v-4865b274=""><br data-v-4865b274=""></div><div data-v-4865b274="" data-v-43a77f0d=""><div data-v-4865b274=""><h2 data-v-4865b274="">🔹 16. When to use interfaces and when to use classes in TypeScript?</h2></div> <div data-v-4865b274="">
    👉🏼 Check
    <a data-v-4865b274="" href="https://devinterview.io/dev/typescript-interview-questions">all 39 answers</a></div> <br data-v-4865b274=""><br data-v-4865b274=""></div><div data-v-4865b274="" data-v-43a77f0d=""><div data-v-4865b274=""><h2 data-v-4865b274="">🔹 17. How could you check null and undefined in TypeScript?</h2></div> <div data-v-4865b274="">
    👉🏼 Check
    <a data-v-4865b274="" href="https://devinterview.io/dev/typescript-interview-questions">all 39 answers</a></div> <br data-v-4865b274=""><br data-v-4865b274=""></div><div data-v-4865b274="" data-v-43a77f0d=""><div data-v-4865b274=""><h2 data-v-4865b274="">🔹 18. Which object oriented terms are supported by TypeScript?</h2></div> <div data-v-4865b274="">
    👉🏼 Check
    <a data-v-4865b274="" href="https://devinterview.io/dev/typescript-interview-questions">all 39 answers</a></div> <br data-v-4865b274=""><br data-v-4865b274=""></div><div data-v-4865b274="" data-v-43a77f0d=""><div data-v-4865b274=""><h2 data-v-4865b274="">🔹 19. What are the difference beetween Typescript and JavaScript?</h2></div> <div data-v-4865b274="">
    👉🏼 Check
    <a data-v-4865b274="" href="https://devinterview.io/dev/typescript-interview-questions">all 39 answers</a></div> <br data-v-4865b274=""><br data-v-4865b274=""></div><div data-v-4865b274="" data-v-43a77f0d=""><div data-v-4865b274=""><h2 data-v-4865b274="">🔹 20. What is a TypeScript Map file?</h2></div> <div data-v-4865b274="">
    👉🏼 Check
    <a data-v-4865b274="" href="https://devinterview.io/dev/typescript-interview-questions">all 39 answers</a></div> <br data-v-4865b274=""><br data-v-4865b274=""></div><div data-v-4865b274="" data-v-43a77f0d=""><div data-v-4865b274=""><h2 data-v-4865b274="">🔹 21. Could we use TypeScript on backend and how?</h2></div> <div data-v-4865b274="">
    👉🏼 Check
    <a data-v-4865b274="" href="https://devinterview.io/dev/typescript-interview-questions">all 39 answers</a></div> <br data-v-4865b274=""><br data-v-4865b274=""></div><div data-v-4865b274="" data-v-43a77f0d=""><div data-v-4865b274=""><h2 data-v-4865b274="">🔹 22. What is Typings in Typescript?</h2></div> <div data-v-4865b274="">
    👉🏼 Check
    <a data-v-4865b274="" href="https://devinterview.io/dev/typescript-interview-questions">all 39 answers</a></div> <br data-v-4865b274=""><br data-v-4865b274=""></div><div data-v-4865b274="" data-v-43a77f0d=""><div data-v-4865b274=""><h2 data-v-4865b274="">🔹 23. What is the default access modifier for members of a class in TypeScript?</h2></div> <div data-v-4865b274="">
    👉🏼 Check
    <a data-v-4865b274="" href="https://devinterview.io/dev/typescript-interview-questions">all 39 answers</a></div> <br data-v-4865b274=""><br data-v-4865b274=""></div><div data-v-4865b274="" data-v-43a77f0d=""><div data-v-4865b274=""><h2 data-v-4865b274="">🔹 24. Is that TypeScript code valid? Explain why.</h2></div> <div data-v-4865b274="">
    👉🏼 Check
    <a data-v-4865b274="" href="https://devinterview.io/dev/typescript-interview-questions">all 39 answers</a></div> <br data-v-4865b274=""><br data-v-4865b274=""></div><div data-v-4865b274="" data-v-43a77f0d=""><div data-v-4865b274=""><h2 data-v-4865b274="">🔹 25. How TypeScript is optionally statically typed language?</h2></div> <div data-v-4865b274="">
    👉🏼 Check
    <a data-v-4865b274="" href="https://devinterview.io/dev/typescript-interview-questions">all 39 answers</a></div> <br data-v-4865b274=""><br data-v-4865b274=""></div><div data-v-4865b274="" data-v-43a77f0d=""><div data-v-4865b274=""><h2 data-v-4865b274="">🔹 26. How To Use external plain JavaScript Libraries in TypeScript?</h2></div> <div data-v-4865b274="">
    👉🏼 Check
    <a data-v-4865b274="" href="https://devinterview.io/dev/typescript-interview-questions">all 39 answers</a></div> <br data-v-4865b274=""><br data-v-4865b274=""></div><div data-v-4865b274="" data-v-43a77f0d=""><div data-v-4865b274=""><h2 data-v-4865b274="">🔹 27. Does TypeScript supports function overloading?</h2></div> <div data-v-4865b274="">
    👉🏼 Check
    <a data-v-4865b274="" href="https://devinterview.io/dev/typescript-interview-questions">all 39 answers</a></div> <br data-v-4865b274=""><br data-v-4865b274=""></div><div data-v-4865b274="" data-v-43a77f0d=""><div data-v-4865b274=""><h2 data-v-4865b274="">🔹 28. Explain how and why we could use property decorators in TS?</h2></div> <div data-v-4865b274="">
    👉🏼 Check
    <a data-v-4865b274="" href="https://devinterview.io/dev/typescript-interview-questions">all 39 answers</a></div> <br data-v-4865b274=""><br data-v-4865b274=""></div><div data-v-4865b274="" data-v-43a77f0d=""><div data-v-4865b274=""><h2 data-v-4865b274="">🔹 29. What are different components of TypeScript?</h2></div> <div data-v-4865b274="">
    👉🏼 Check
    <a data-v-4865b274="" href="https://devinterview.io/dev/typescript-interview-questions">all 39 answers</a></div> <br data-v-4865b274=""><br data-v-4865b274=""></div><div data-v-4865b274="" data-v-43a77f0d=""><div data-v-4865b274=""><h2 data-v-4865b274="">🔹 30. How can you allow classes defined in a module to accessible outside of the module?</h2></div> <div data-v-4865b274="">
    👉🏼 Check
    <a data-v-4865b274="" href="https://devinterview.io/dev/typescript-interview-questions">all 39 answers</a></div> <br data-v-4865b274=""><br data-v-4865b274=""></div><div data-v-4865b274="" data-v-43a77f0d=""><div data-v-4865b274=""><h2 data-v-4865b274="">🔹 31. What's wrong with that code?</h2></div> <div data-v-4865b274="">
    👉🏼 Check
    <a data-v-4865b274="" href="https://devinterview.io/dev/typescript-interview-questions">all 39 answers</a></div> <br data-v-4865b274=""><br data-v-4865b274=""></div><div data-v-4865b274="" data-v-43a77f0d=""><div data-v-4865b274=""><h2 data-v-4865b274="">🔹 32. Are strongly-typed functions as parameters possible in TypeScript?</h2></div> <div data-v-4865b274="">
    👉🏼 Check
    <a data-v-4865b274="" href="https://devinterview.io/dev/typescript-interview-questions">all 39 answers</a></div> <br data-v-4865b274=""><br data-v-4865b274=""></div><div data-v-4865b274="" data-v-43a77f0d=""><div data-v-4865b274=""><h2 data-v-4865b274="">🔹 33. What is the difference between "interface vs type" statements?</h2></div> <div data-v-4865b274="">
    👉🏼 Check
    <a data-v-4865b274="" href="https://devinterview.io/dev/typescript-interview-questions">all 39 answers</a></div> <br data-v-4865b274=""><br data-v-4865b274=""></div><div data-v-4865b274="" data-v-43a77f0d=""><div data-v-4865b274=""><h2 data-v-4865b274="">🔹 34. What is one thing you would change about TypeScript?</h2></div> <div data-v-4865b274="">
    👉🏼 Check
    <a data-v-4865b274="" href="https://devinterview.io/dev/typescript-interview-questions">all 39 answers</a></div> <br data-v-4865b274=""><br data-v-4865b274=""></div><div data-v-4865b274="" data-v-43a77f0d=""><div data-v-4865b274=""><h2 data-v-4865b274="">🔹 35. Explain when to use "declare" keyword in TypeScript</h2></div> <div data-v-4865b274="">
    👉🏼 Check
    <a data-v-4865b274="" href="https://devinterview.io/dev/typescript-interview-questions">all 39 answers</a></div> <br data-v-4865b274=""><br data-v-4865b274=""></div><div data-v-4865b274="" data-v-43a77f0d=""><div data-v-4865b274=""><h2 data-v-4865b274="">🔹 36. Is it possible to generate TypeScript declaration files from JS library?</h2></div> <div data-v-4865b274="">
    👉🏼 Check
    <a data-v-4865b274="" href="https://devinterview.io/dev/typescript-interview-questions">all 39 answers</a></div> <br data-v-4865b274=""><br data-v-4865b274=""></div><div data-v-4865b274="" data-v-43a77f0d=""><div data-v-4865b274=""><h2 data-v-4865b274="">🔹 37. What are Ambients in TypeScripts and when to use them?</h2></div> <div data-v-4865b274="">
    👉🏼 Check
    <a data-v-4865b274="" href="https://devinterview.io/dev/typescript-interview-questions">all 39 answers</a></div> <br data-v-4865b274=""><br data-v-4865b274=""></div><div data-v-4865b274="" data-v-43a77f0d=""><div data-v-4865b274=""><h2 data-v-4865b274="">🔹 38. Explain why that code is marked as WRONG?</h2></div> <div data-v-4865b274="">
    👉🏼 Check
    <a data-v-4865b274="" href="https://devinterview.io/dev/typescript-interview-questions">all 39 answers</a></div> <br data-v-4865b274=""><br data-v-4865b274=""></div><div data-v-4865b274="" data-v-43a77f0d=""><div data-v-4865b274=""><h2 data-v-4865b274="">🔹 39. How would you overload a class constructor in TypeScript?</h2></div> <div data-v-4865b274="">
    👉🏼 Check
    <a data-v-4865b274="" href="https://devinterview.io/dev/typescript-interview-questions">all 39 answers</a></div> <br data-v-4865b274=""><br data-v-4865b274=""></div></div>
