# `info-code`
Aiming for a minimal simple model to describe code information. (Things that matter), where typescript is not required...  
> JS: javascript  
> TS: typescript  

Typescript is a superset of javascript, which mainly used to provide static typing, to prevent mistakes of dynamic typing. afterwards they add more tooling and principles such as OOP concepts, etc... which might be useful in specific use-cases, such as:  

- static typing, constraints, custom types, OOP principles such as interfaces, encapsulation,...
- preventing ambiguity, mistakes or intentional altered code by a bad/noob/careless developer.
- streamlining dev-team with rules and constrained setup preventing the to mistake or get out of the line
- non-JS traditional non web programmers mindset,... but going full TS is overrated hype and not valid.  

The general assumption is TS prevents bugs, clarifies intent, safety etc... which in fact depends on:  
- Developer + development model -> dev-structure-pattern, implementation, tools, best practices, code readability, integration...
- Run-time process: usually all TS is removed at compilation/build-time, before is executed on a JS runtime.
- Run-time data/input:  sanitize inputs, unit and in specific integration testing is effective.  

`To summarize`: some of typescipt's abilities might come useful in your dev cycle/env, when used at the correct time/place, but going all TS by trend might negetively impact your dev productivity.  
  
 ***

### `TS Pros`:
* easier traversal of annotated objects
* better schema definitions for functions and classes
* type safety, early warnings on improper usage, and yes, sometimes safer code like having to check for null
* easier inline documentation for those that can read TS
* beneficial to developers coming from static typed languages mindset, (C++, C#, Java...)

### `TS Cons`:
* JS must be a valid TS but in practice JS developer or code might not be able to integrate with TS.
* discards JS dynamic pattern and mindset, which is productive, simple and in specific cases is required.
* concentrates only on dev/env time, at the build/run-time TS code is removed, code safety is up to runtime.
* learning curve + bad learning (using it in wrong places and not using it where is practical)
* double standards/rules in JS eco-system, which is forced by TS devs, and is non productive.
* un-readable + unexpected code behavior: if complex/custom type systems are badly architected.
* env dependencies and library workarounds at times of lacking support.
* false assumption of TS -> (prevents bugs + error free + team understands my TS) -> devaluing of unit/integration testing
* DRY -> (redundant + unnecessary TS code pollution): typing,...etc at multiple places where one was enough and effective.  

### `Final thoughts`:
At present time IDE's (EX: VScode) frameworks(EX: Svelte/kit), methods/libs/tools such as testing will use TS under the hood or inform the user in a better way than the TS itself, considering future progress of native progress of JS and AI automation, typescript intention can be handled without polluting the code, just the intent matters, therefore in my oppinion is best to adopt better JS practices and strategies and using new native system to keep your work standard and unpolluted, at the mean-time use TS as a tool only where applies for the benefits rather than upholding it as a new language.
