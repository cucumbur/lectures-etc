* Today I’m going to talk about programming languages, and how to make choices about which ones to use based on what you plan to do. Since programming is the basically synonymous with development, it’s an important choice.
* Why does it matter what language you choose?
 * "The diversity of languages is not a diversity of signs and sounds but a diversity of views of the world” (Von Humboldt)
   * (the choice of a programming language is more than an aesthetic decision)
   * even languages with a similar syntax can serve entirely different purposes
 * Technical considerations
    * The platforms you’re targeting may require a specific language (i.e. Swift or Objective-C for native iOS development)
    * The platform you are targeting for may be hard to compile to/run on for many languages (i.e. microcontrollers can run C code, but probably not a JVM or Node)
    * You may need low-level features not accessible in a higher-level language (i.e. writing drivers for embedded devices in C or Assembly)
    * Languages differ dramatically in speed, a resource intensive project may require a generally faster language
 * Practical considerations
    * You may want certain high-level features and existing libraries so you don’t have to reinvent the wheel
    * You already know a language, so you don’t have to learn anything new
    * Using a de facto industry/community standard language means more people will be able to work on/contribute to a commercial/open source project
    * The documentation of languages can range from nonexistent to transcendent
    * Good tooling can be important if you’d rather not spend tons of time figuring everything out
    * A language may have more robust features for enterprise-scale codebases (error-handling, etc)
    * Quick prototypes may warrant a language that is lighter and easier to iterate rapidly, large projects may benefit from languages with more structure and maintanibility
    * The community surrounding a language is important
 * Different programming languages foster different ways of thinking about problems
   * “[Programming languages] powerfully condition all our thinking about social problems and processes. Human beings … are very much at the mercy of the particular language which has become the medium of expression for their [codebase]” (Sapir…. paraphrased)
 * Examples
    * Finding a path between two nodes
    * Quicksort
* Explanation of common language features/paradigms
 * Static vs Dynamic typing
    * Static: stalwart of many more traditional/enterprise languages, lengthier code but with more assurances about what your code represents
    * Dynamic: generally more attractive and lean syntax, lack of type checking can introduce headaches for debugging and code collaboration
 * Imperative vs Functional (or, technically, declarative)
    * Imperative: the “standard” for most programming. everyone is trained to think of writing algorithms and programs in this way. they can be very efficient. You give commands to the machine, hence imperative 
    * Functional: you describe the way your program works, not give a list of commands. The same inputs always produce the same outputs 
 * High Level vs Low Level
    * High level: abstractions that remove the need to do a lo or minor, repetative tasks. garbage collection, 
    * Low level:closer access to the nitty gritty 
 * Interpreted vs Compiled
    * Interpreted: you use the source code itself every time you run it, and the interpreter figures out what to do 
    * Compiled: when you have an executable, binary file compiled for only one type or computer. 
 * Object Oriented
    * Important programming paradigm that solves a lot of problems
    * but people also try and make any problem fit into the OOP way of thinking, and this doesnnt really work
    * "The problem with object-oriented languages is they've got all this implicit environment that they carry around with them. You wanted a banana but what you got was a gorilla holding the banana and the entire jungle.” (Joe Armstrong)
* Languages
  * Python
    * "high-level, general-purpose, interpreted, dynamic"
    * New programmers
    * Scientific computing, mathematics, "data science” and statistics
    * Web backend
    * Prototyping
    * CLI tools
    * All around utility language
  * JavaScript
    * high level, Untyped/dynamic, interpreted
    * THE web standard
    * front end scripting
    * server side scripting (node.js)
    * node.js for backends in general - APIs + etc
    * rapid prototyping / development
    * very prominent community on the web and in programmer circles, good place to get involved in a community
    * has libraries to accomplish almost anything you could need
    * generally not a great choice for many larger projects, as it can be hard to maintain because of not having types
    * also, the community moves so fast that all your tools and frameworks are replaced by new ones constantly, and it can be a huge hassle
  * C
    * “low-level"
    * Static, imperative 
    * the point of comparison for all modern programming languages
    * easy to get yourself into trouble (see CS241)  - dont use lightly
    * low level access to memory and system level functionality
    * no OO
    * Embedded devices
    * Operating systems
  * C++
    * Older Brother of c
    * Imperative and static like c but with OOP
    * Great for high performance apps like games and graphics software 
    * It can be difficult to use
  * Java
    * Object oriented, static, imperative 
    * JVM
    * Works anywhere 
    * Android development
  * C#
    * Java, by Microsoft
    * A very modern OOP language
    * If you want to develop for Windows, this is your best choice
  * Ruby
    * dynamic scripting language
    * Ruby used to be as big for web development JavaScript, but its fading in popularity
    * nonetheless, it has a great syntax
    * Still has one of the most widely used web frameworks, Ruby on Rails
  * PHP
    * Not really used anymore, not a whole lot of reason to use this but you may see it if you work with time travelers from 2003
    * But, a lot of older codebases, especially open source ones, might use this. (like wordpress)
  * Slightly esoteric: Haskell, Prolog, Lisp, Erlang
    * A little more academic or niche, but they serve great purposes
    * Haskell lets you think really logical about your programs. It’s great for developing compilers and interpreters and programming languages.
    * Prolog is a bizarre logic programming language. All you have to do is describe the relationships on your data, and it will run the algorithms for you
    * Lisp is like… the ultimate programming language. Everyone who knows it seems to possess magical capabilities
    * Erlang is a language that is unparalleled in… parallelization and fault tolerance (can recover from errors). COD servers run on erlang. many phone networks use erlang to handle their connections.
  * Newcomers: Rust, Go, Swift, Crystal
    * Rust has mozillas backing. it’s a system language: an alternative to C with some nice tooling
    * Go is a general purpose language backed by google. also great tooling.
    * Swift is backed by Apple. it’s used for iOS development along with Objective-C.
    * Crystal is Ruby, but fast!
