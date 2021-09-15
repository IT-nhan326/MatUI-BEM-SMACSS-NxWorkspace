## [Material UI](https://material-ui.com/getting-started/installation/)

## [BEM Methodolody](https://en.bem.info/methodology/key-concepts/) :  Block | Element | Modifier  - HTML/CSS naming convention
### 1. Block : 
  - Block is the top-level abstraction of a new component 
  - Example : .btn {}
### 2. Elenment (child item) : 
  - Element can be placed inside "block", these are denoted by two underscores following the name of the block
  - Example : .btn__text {}
### 3. Modifier : 
  - Modifiers can manipulate the block, so that we can theme or style that particular component without inflicting changes on a completely unrelated module. 
  - This is done by appending two hyphens to the name of the block
  - Example : .btn--white {}
### 4. Note:
  * .nav .nav__listItem .btn--orange is not BEM. 
  * Because .nav(Block) will override the style of .btn--orange(Modifier) which must not happen in [BEM].

## [SMACSS](http://smacss.com) : Scalable and Modular Architecture for CSS
### **1. Base Rules** : 

### **2. Layout Rules** : divide the page into sections. Layouts hold one or more modules together.

### **3. Modules Rules** : are the reusable, modular parts of our design. They are the callouts, the sidebar sections, the product lists and so on.

### **4. State Rules** : 
  - Are ways to describe how our modules or layouts will look when in a particular state.
  - Hidden or expanded
  - Active or inactive
  - They are about describing how a module or layout looks on screens that are smaller or bigger
  - Describing how a module might look in different views like the home page or the inside page

### **5. Theme Rules** : 
  - Are similar to state rules in that they describe how modules or layouts might look. 
  - Most sites don’t require a layer of theming but it is good to be aware of it.

## [Nx WorkSpace](https://nx.dev/) : Nx is a set of extensible dev tools for monorepos, which helps you develop like Google, Facebook, and Microsoft.

