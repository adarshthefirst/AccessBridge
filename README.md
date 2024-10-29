# AccessBridge
AccessBridge is the practice of making websites usable for all visitors, including those with disabilities, impairments, and limitations. ``"index.js"`` makes you to navigate all the focusable elements on a web page using arrow keys (↑ ↓ → ←) adding a simple class arrow-navigable.

## Arrow Key Navigation

This tool enables navigation using keyboard arrow keys between a HTML document's elements. It supports automatic detection of the most sensible element to jump to when hitting arrow keys. It doesn't impose a rule on the type of the element it can work with.

## Installation

```
<script src="https://raw.githubusercontent.com/adarshthefirst/AccessBridge/627d57a552506a2f56ba145bb5c019379296d26c/index.js">
```


## API

Add the class ``"arrow-navigable"`` to each element you want to enable keyboard navigation for. 
e.g. ```<div className="arrow-navigable"></div> ```

### setNavigableClassName(className) 
change the default "arrow-navigable" to a class name of your choosing. 

```
import {setNavigableClassName} from "arrow-key-nav" 
setNavigableClassName("my-navigable-element");
