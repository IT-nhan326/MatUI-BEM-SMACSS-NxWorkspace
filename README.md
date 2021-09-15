## [Material UI](https://material-ui.com/getting-started/installation/) : React Component Framework

## [BEM Methodolody](https://en.bem.info/methodology/key-concepts/) :  Block | Element | Modifier  - HTML/CSS naming convention
### 1. Block : 
  - Block is the top-level abstraction of a new component.
  - Example : .btn {}
### 2. Elenment (child item) : 
  - Element can be placed inside "block", these are denoted by two underscores following the name of the block.
  - Example : .btn__text {}
### 3. Modifier : 
  - Modifiers can manipulate the block, so that we can theme or style that particular component without inflicting changes on a completely unrelated module. 
  - This is done by appending two hyphens to the name of the block.
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
  - Hidden or expanded.
  - Active or inactive.
  - They are about describing how a module or layout looks on screens that are smaller or bigger.
  - Describing how a module might look in different views like the home page or the inside page.

### **5. Theme Rules** : 
  - Are similar to state rules in that they describe how modules or layouts might look. 
  - Most sites don’t require a layer of theming but it is good to be aware of it.

## [Nx WorkSpace](https://nx.dev/) : Nx is a set of extensible dev tools for monorepos
### **1. Monorepos** : 
  1. **A monorepo (mono repository)** is a single repository that stores all of your code and assets for every project.
  2. **Monorepo vs. Monolith** : A monorepo is a single repository. A monolith is a massive codebase.
  3. **Monorepo vs. Multirepo** : [Source](https://www.perforce.com/blog/vcs/what-monorepo) 
      * A monorepo keeps everything in one repository. 
      * A multirepo (multiple repositories) typically has one repository for each project. The more projects, the more repositories. A multirepo is also known as polyrepo.
  4. **Monorepo is best for** : 
      * _Visibility_ : Using a single repository gives you visibility into your code and assets for every project. This helps you manage dependencies.
      * _Colaboration_ : A single repository makes it easier to collaborate. That’s because everyone can access the code, files, and assets. So, developers can share and reuse assets.
      * _Speed_ : Using a single repository can help you accelerate development. For instance, you can make atomic changes (one action to make a change across multiple projects).
  5. **Multirepo is best for** : 
      * _Git Projects_ : Managing a monorepo at scale in Git would never work. As the repository gets bigger, a monorepo in Git becomes a huge problem. So if you have teams using Git, it’s best to have multiple repositories.
      * _Another Git problem_ : Git lack security (must lock down Git)
      * _Open Source or Third Party Projects_ : In some version control systems, you’ll need multiple repositories to use open source projects or work with third party teams. Then you can ensure that third party developers only have access to the project they're working on.

