build-lists: true

# [fit][Web Assembly Dance Party](https://www.youtube.com/watch?v=ojP0BO6H4Qc)

![inline](https://media.giphy.com/media/l3q2zbskZp2j8wniE/giphy.gif)

---

# [fit]Learn a Language: Web Assembly

![inline](https://upload.wikimedia.org/wikipedia/commons/thumb/c/c6/Web_Assembly_Logo.svg/1200px-Web_Assembly_Logo.svg.png)

---

# Who is this guy? (@seanhelvey)
* M.S. Computer Science at New York University
* Web Development Instructor at Galvanize Boulder
* Teacher of JavaScript, Node.js, React, Redux
* Co-organizer of Front Range Elm Meetup

---

# I do not work for a browser vendor!
* Most talks you will find on WebAssembly are biased
* Not saying this is a bad thing, but let's be honest
* Also not trying to compile my C++ game to the web
* I'm an average web developer interested in the future

---

# Objectives
* Illustrate growth of ECMAScript
* Introduce WebAssembly (Wasm)
* Understand how to use Wasm
* Outline future vision

---

# Discuss growth of ECMAScript specification
* 1995: JavaScript created
* 1997: *110* page ECMAScript specification
* 2015: *566* page ECMAScript specification

---

![inline](./Images/JavaScriptGrowth.png)

---

# Back in the day

![inline](./Images/Wasm1.png)

---

# 5-10 years ago

![inline](./Images/Wasm2.png)

---

# Yesterday

![inline](./Images/Wasm3.png)

---

# THE FUTURE (Today)

![inline](./Images/Wasm4.png)

---

# Indirect flight: CO -> Europe -> Hawaii

![inline](./Images/map1.png)

---

# Direct flight: CO -> Hawaii

![inline](./Images/map2.png)

---

# A student / teacher perspective on WebAssembly
* I’ve used over 20 different languages and trust me
* Teaching JavaScript is the hardest by far
* ES5 was hard to begin with
* ES6, 7, 8, etc. making it even more difficult

---

![inline](./Images/FrozenSpecTweet.png)

---

# Timeline of WebAssembly developments
* March 2013 - Predecessor asm.js released
* June 2015 - WebAssembly working group formed
* November 2017 - WebAssembly MVP released
* February 2018 - W3C public draft released

---

# .wat is WebAssembly or Wasm?
* A binary instruction format for a virtual machine
* A portable target for high-level languages
* Java / JVM solved similar portability issue

---

# .wat is WebAssembly or Wasm (Cont...)
* 32 and 64 bit integer and floating point types
* File formats

![inline](./Images/CppHello.png)

---

# .wat is WebAssembly or Wasm (Cont...)
* Modules can be loaded in either the UI thread or in a Web Worker
* Run in a safe, sandboxed execution environment & enforces browser's policies and permissions

---

# Memory
* Wasm Memory is represented as a contiguous range of untyped bytes
* The memory accessible by a particular WebAssembly Instance is confined to a range
* Libraries have separate memories that are fully isolated from each other

---

# Tables
* Wasm Tables are resizable typed arrays of references
* While Memory provides a resizable typed array of raw bytes, it is unsafe for references
* In the current iteration, functions are the only valid reference type

---

# How can I use it?

![inline](./Images/LaurieVossWasmTweet.png)

---

# wasm-bindgen

![inline](./Images/wasm-bindgen-snippet.png)

---

# Emscripten

* When you’ve written a new code module in a language like C/C++, you can compile it into WebAssembly using a tool like Emscripten

`emcc hello.c -s WASM=1 -o hello.html`

---

# Future vision
* Is it really just for C/C++/Rust?
* Language quality race to the top
* More modularity and portability
* JavaScript (maybe) as glue code
* Choose the right tool for the job!

---

# Objectives
* Illustrate growth of ECMAScript
* Introduce WebAssembly (Wasm)
* Understand how to use Wasm
* Outline future vision

---

# Thank you!

![inline](https://d1wli5mq9yq9mw.cloudfront.net/files/cards/full/VIVA111.png)
