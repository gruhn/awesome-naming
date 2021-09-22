# Awesome Naming [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

<!-- lint disable no-repeat-punctuation -->
Famously...
<!-- lint enable no-repeat-punctuation -->

> There are only two hard things in Computer Science: cache invalidation and naming things.
> 
> ― Phil Karlton

Concepts in computer science are usually nothing tangible so it's no surprise that naming things is hard.
Nevertheless, we _do_ come up with clever, creative and funny names.
Some of them so established, we never pause and admire.

This is a curated list for when naming things is done right.

## Contents 

- [Data Structures and Algorithms](#data-structures-and-algorithms)
- [Design Patterns and Anti Patterns](#design-patterns-and-anti-patterns)
- [Functions](#functions)
- [IT Security](#it-security)
- [Libraries and Frameworks](#libraries-and-frameworks)
- [Machine Learning](#machine-learning)
- [Theoretical Computer Science](#theoretical-computer-science) 
- [User Interface Design](#user-interface-design)
- [Other](#other)

---

## Data Structures and Algorithms

- [Brute force](https://en.m.wikipedia.org/wiki/Brute-force_search) - Violence is actually almost always a solution but not a very clever one.
- [Greedy algorithm](https://en.wikipedia.org/wiki/Greedy_algorithm) - An algorithm that finds a solution by always picking the currently best looking option without thinking too much about past and future decisions.
- [Hill climbing](https://en.wikipedia.org/wiki/Hill_climbing) - Starting somewhere in the hilly "landscape" of solutions you go in the direction of steepest ascent until reaching the top of a hill. You might miss higher hills though. 
- [Israeli Queue](https://rapidapi.com/blog/israeli-queues-exploring-a-bizarre-data-structure/) - A type of priority queue and a reference to the infamously unorganized queues in Israel. Here items can *cut in line* when they *have already waiting friends*.
- [Stack](https://en.wikipedia.org/wiki/Stack_(abstract_data_type)) - Like with a stack of pancakes you can only add and remove items from the top of this data structure.
- [Tree](https://en.wikipedia.org/wiki/Tree_(data_structure)) - A hierarchically organized data structure. From the _root_ item the other items _branch out_ into _nodes_ and _leaves_.
- [Queue](https://en.wikipedia.org/wiki/Queue_(abstract_data_type)) - In this data structure items are always added at the end and removed at the front as if the items were waiting in line.

## Design Patterns and Anti Patterns

- [Adapter](https://en.wikipedia.org/wiki/Adapter_pattern) - Allows classes with incompatible interfaces to work together by wrapping its own interface around that of an already existing class.
- [Facade](https://en.wikipedia.org/wiki/Facade_pattern) - Analogous to a facade in architecture, a facade is an object that serves as a front-facing interface masking more complex underlying structure.
- [Promise](https://en.wikipedia.org/wiki/Futures_and_promises) - A representation of a result that is available in the future, unless there are errors. Like in reality, promises are broken sometimes.
- [Shotgun surgery](https://en.wikipedia.org/wiki/Shotgun_surgery) - A programming antipattern where in a single change you wildly add code everywhere in your codebase.

## Functions

- [fold](https://en.wikipedia.org/wiki/Fold_(higher-order_function)) - Like a blanket being folded up, this function iterates a collection and in each step combines the current item with everything that has already been folded.
- [trampoline](https://clojuredocs.org/clojure.core/trampoline) - Continuously runs functions which itself return functions. Like a child on a trampoline that _returns_ and bounces back up. 
- [zip](https://hackage.haskell.org/package/base-4.12.0.0/docs/Prelude.html#v:zip) - Merges two lists into one list of pairs like the interlocking teeth of a zipper.

## IT Security

- [Backdoor](https://en.wikipedia.org/wiki/Backdoor_(computing)) - A method of bypassing normal authentication in a computer system.
- [Computer virus](https://en.wikipedia.org/wiki/Computer_virus) - A computer program that self replicates by _infecting_ other computer programs similar to the behavior of biological viruses.
- [Cyber hygiene](https://digitalguardian.com/blog/what-cyber-hygiene-definition-cyber-hygiene-benefits-best-practices-and-more) - Steps and practices that users should take to maintain system health and improve online security.
- [Honeypot](https://en.wikipedia.org/wiki/Honeypot_(computing)) - Part of a system meant to look like an attractive target but actually helps detect and deflect attackers.
- [Phoning home](https://en.wikipedia.org/wiki/Phoning_home) - When a system (e.g. stolen computer) secretly reports back to a third party other than the current possessor. The name is a reference to the movie E.T.
- [Sandbox](https://en.wikipedia.org/wiki/Sandbox_(computer_security)) - A safe and isolated environment to test unverified programs that may contain malicious code.
- [Trojan horse](https://en.wikipedia.org/wiki/Trojan_horse_(computing)) - Malware which misleads users of its true intent. The term is derived from the Ancient Greek story of the deceptive Trojan Horse. 

## Libraries and Frameworks

- [clooney](https://github.com/GoogleChromeLabs/clooney) - A JavaScript library implementing the actor model for concurrent computation. The term is a reference to George Clooney who is also an actor.
- [Uglify](https://github.com/mishoo/UglifyJS) - A JavaScript minifier. Removes everything that makes the code readable and pretty to make it smaller.
- [uppy](https://github.com/transloadit/uppy) - A dog themed uploader component. The name is a blend of _upload_ and _puppy_. It even comes with a crash recovery plugin called _Golden Retriever_.

## Machine Learning

- [Confusion matrix](https://en.wikipedia.org/wiki/Confusion_matrix) - A tabular summary of a classifiers "confusion", i.e. how often it thought to make correct predictions when it actually didn't.
- [Decision boundary](https://en.wikipedia.org/wiki/Decision_boundary) - A boundary dividing the space of possible data points. Here you decide, everything on this side is SPAM, everything on that side is not. 

## Programming Languages

- [Clojure](https://clojure.org/) - A functional language making extensive use of **closures** but with a **j** because it's running on the Java virtual machine.
- [C++](https://en.wikipedia.org/wiki/C%2B%2B#External_links) - The successor of **C** indicated by the iconic increment operator **++**.

## User Interface Design

- [Breadcrumb](https://en.wikipedia.org/wiki/Breadcrumb_(navigation)) - Navigational aid allowing users to keep track of their location within programs, documents, or websites. The term is a reference to the fairy tale _Hansel and Gretel_.
- [Carousel](https://www.nngroup.com/articles/designing-effective-carousels/) - A kind of animated slideshow looping back on itself.
- [Clipboard](https://en.wikipedia.org/wiki/Clipboard_(computing)) - Where you temporarily put _files_ you are working with (i.e. the copy & paste buffer).
- [Desktop](https://en.wikipedia.org/wiki/Desktop_metaphor) - The metaphorical top of the user's desk, upon which objects such as documents and folders of documents can be placed.
- [Hamburger button](https://en.wikipedia.org/wiki/Hamburger_button) - A button to toggle a menu. The associated icon resembles a hamburger.
- [Optimistic UI](https://uxplanet.org/optimistic-1000-34d9eefe4c05) - User interfaces that assume expensive operations will complete successfully thereby improving the perceived performance.
- [Scrolling](https://en.wikipedia.org/wiki/Scrolling) - Screen content is often less like a book with discrete pages and more like a continuous roll of parchment, i.e. a scroll.

## Theoretical Computer Science

- [Clique problem](https://en.wikipedia.org/wiki/Clique_problem) - The problem of finding groups of mutual friends in a network of people with friendship relations. Or more general, finding complete subgraphs.
- [Game of Life](https://en.wikipedia.org/wiki/Conway%27s_Game_of_Life) - A game world that showcases how astonishing complexity can arise from very simple ingredients.
- [Oracle](https://en.wikipedia.org/wiki/Oracle_machine) - A black box that magically gives answers even to undeciable questions like the halting problem. 
- [Pumping lemma](https://en.wikipedia.org/wiki/Pumping_lemma) - The fact that in some formal languages any sufficiently long string can be _pumped_ with repetitions of its substring and the result stays in the same formal language.

## Other

- [ACID vs. BASE](https://www.johndcook.com/blog/2009/07/06/brewer-cap-theorem-base/) - Acronyms describing competing database ideologies (aka. SQL vs. NoSQL). 
- [Bottleneck](https://en.wikipedia.org/wiki/Bottleneck#Computing) - A central part of a network/application that significantly limits throughput/performance and should ideally be eliminated.
- [camelCase, snake_case, kebab-case](https://en.wikipedia.org/wiki/Letter_case#Special_case_styles) - Different case styles where the name illustrates its appearance.
- [Easter egg](https://en.wikipedia.org/wiki/Easter_egg_(media)) - A hidden feature especially in video games in reference to the Easter egg hunt.
- [Floating point number](https://floating-point-gui.de/formats/fp/) - This representation can encode numbers at very different magnitudes with limited amount of digits by letting the radix point _float_ instead of being fixed in place.
- [Framework](https://en.wikipedia.org/wiki/Software_framework) - In software architecture (like in actual architecture) frameworks provide basic structure to  build upon that guide and constrain the further development.
- [Garbage Collector](https://en.m.wikipedia.org/wiki/Garbage_collection_(computer_science)) - Part of a program that attempts to find and reclaim garbage pieces of memory not used anymore.
- [Glue Code](https://en.wikipedia.org/wiki/Glue_code) - Jenga and LEGO bricks don't share the same interface but you can always glue them together.
- [Heisenbug](https://en.wikipedia.org/wiki/Heisenbug) - A bug that seems to disappear or change when one tries to study it. It's a pun on Werner Heisenberg who discovered that the act of observing quantum systems inevitably alters their state.
- [Lazy evaluation](https://en.wikipedia.org/wiki/Lazy_evaluation) - An evaluation stategy which suspends evaluation until it's absolutly necessary and then never does it again.
- [Magic](https://en.wikipedia.org/wiki/Magic_(programming)) - A magic program/piece of code is doing it's job but nobody knows how. Like in reality, magic doesn't actually exists. Once you understand it, it's not magic anymore.
- [Process starvation](https://en.wikipedia.org/wiki/Starvation_(computer_science)) - A problem where a process is perpetually denied resources to do its work.
- [Time travel debugging](https://en.wikipedia.org/wiki/Time_travel_debugging) - Stepping back in time through source code to understand execution and sometimes even to change history.
- [Tree shaking](https://en.wikipedia.org/wiki/Tree_shaking) - Shake the dependency tree until all the dead parts are falling off and you end up with a nice lean tree.
