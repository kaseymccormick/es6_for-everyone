#Notes
My collection of notes while going through each video for ES6 for everyone. Organized by video first and then likely reorganized later.

### Module 1 variables

scoping variables available are Var, Let, and Const

*Var* 
can be reassigned 
can be updated or redefined. 
available inside the function they are created 
globably scoped if not created within a function
var variables are function scoped so if you use it within a conditional it leaks globally

*Let*
block scoped, not function scoped
let will not let you redeclair it twice in same scope
if declaired outside of block then used within block, will not read eachother [block scoping vs function scope]

*Const*
block scoped, not function scoped
can not be updated
stands for constant
attributes can be changed, but not the object
````
const person = {
  hairColor: "blond"
  age: "32"
}
````

