# Check my shit collection
A collection of really useful tools to improve your code quality.
The conception of three "standards" is used in this collection to describe three different levels of code-quality.

## What is a conception of three standards?
This collection contains helpers and presents for the following standards: `bronze`, `silver`, `gold`.
The higher the standard, the more stringent rules.
This standards are applied where it's possible.
For example, for [linters](#use-code-quality-tools-(linters)) I can define configuration files for every standard.
But there is no reason to define [configuration files for ide](#use-editor-config) for each standard because the basic rules are the same.
Difference between each standard was described in each section of the collection (where it's possible).

### :star: `Bronze` standard :beginner:
**In case of code quality tools**

Used for projects that "needed to be done yesterday".
Usually repeats the configuration of an ide and no special more features.
Can be supported with `.editorconfig` and some settings in ide.

### :star: :star: `Silver` standard :guardsman:
**In case of code quality tools**

For "good" projects.
Nothing special.

### :star: :star: :star:`Gold` standard :godmode:
**In case of code quality tools**

Only for **gods-of-js**.


## What I'd suggest to use to improve code quality?
### Use editor config
You can easily support quality of your code with configuration files for your ide.
It is extremely useful with combination of code auto-reformatting.
[Read more about configuration file for ide](/docs/editor/readme.md).

### Use code quality tools (linters)
You can easily support quality of your code with this tools.
Just add them to your project and use configuration files from this collection.
[Read more about configuration files for linters in this collection](/docs/linters/readme.md).

## To be done
- [ ] **Silver standard (default)**
- - [x] Describe `javascript` linter: basic `.eslintrc`, how to use and examples.
- - [x] Describe `stylus` linter: basic `.stylintrc`, how to use and examples.
- - [ ] Describe `css` linter: basic `.csslintrc`, how to use and examples.
- - [ ] Describe `sass` linter: basic `.sasslintrc`, how to use and examples.
- - [ ] Describe `editorconfig`.
- [ ] **Bronze standard**
- [ ] **Gold standard**
