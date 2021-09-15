## [Material UI](https://material-ui.com/getting-started/installation/)

## **BEM Methodolody** :  Block | Element | Modifier  - HTML/CSS naming convention
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
