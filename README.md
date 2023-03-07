# info-code
A simple model to describe code information. (Things that matter), where typescript is not required...  
> JS: javascript  
> TS: typescript  

Typescript is a superset of javascript, useful in specific use-cases, dev team setup... but in most cases the usage is overrated and not valid.  
The assumtion is typescript prevents bugs, clarifies intent, safety etc... which in fact is based on developer itself, dev-structure implemented,
best practices, code readability, and integrated safety.  
To summarize: some of typescipt's abilities comes useful in our dev environment but not the full usage.  

### TS Pros:
* easier traversal of annotated objects
* better schema definitions for functions and classes
* type safety, early warnings on improper usage, and yes, sometimes safer code like having to check for null
* easier inline documentation for those that can read TS
* beneficial to developers coming from static typed languages mindset, (C++, C#, Java...)

### TS Cons:
* JS must be a valid TS but in practice JS developer or code might not be able to integrate with TS.
* discarding JS pattern and mindset, such as simplicity, Dynamic typing, ...
* only works at the development time, at the run-time TS is removed
* extra learning curve, which is non productive.
* if architecting types and type systems done poorly code can be unreadable.
* env dependencies and library workarounds at times of lacking support.
* false sense of 'error free' and (depending on team experience) a devaluing of unit testing due to the assumption that TS prevents bugs
