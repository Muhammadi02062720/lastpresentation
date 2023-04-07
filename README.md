> # What is module in js ?
 >A module is just a file. One script is one module
  >A module is just a piece of code in a file that you can call and use from other files. A modular design is the opposite of having all your project's code in one single file.

  ![](https://www.pvsm.ru/images/2020/06/14/Module-Federation-v-Webpack-5-plagin-dlya-obmena-modulyami-mejdu-Javascript-prilojeniyami-opisanie-i-primer.png)

When developing a big project, it's very useful to divide our code into modules for the following reasons:

1. It's good for dividing concerns and features into different files, which helps visualization and organization of code.
2. Code tends to be easier to maintain and less prone to errors and bugs when it's clearly organized.
3. Modules can be easily used and reused in different files and parts of our project, without needing to rewrite the same code again.

>Instead of having all of our program's components in a single file, we can divide it into parts or modules, and make each of them responsible for a single feature/concern.

![](https://github.com/Muhammadi02062720/Presentation-week-4-last-/raw/master/Screenshot_6.png)

># Types of Module: 

 >Modules can load each other and use special directives export and import to interchange functionality, call functions of one module from another one:

1. export - keyword labels variables and functions that should be accessible from outside the current module.
2. import - allows the import of functionality from other modules.


>## What is import in js ?

 >The static import declaration is used to import read-only live bindings which are exported by another module. The imported bindings are called live bindings because they are updated by the module that exported the binding, but cannot be re-assigned by the importing module.

In order to use the import declaration in a source file, the file must be interpreted by the runtime as a module. In HTML, this is done by adding type="module" to the <script> tag. Modules are automatically interpreted in strict mode.

![](https://i.stack.imgur.com/uCCXS.png)

>## What is export in js ?

 >What is export?
The export statement is used when creating JavaScript modules to export functions, objects, or primitive values from the module so they can be used by other programs with the import statement.

So basically it is used in a JavaScript files to make objects visible to other files (modules).

![](https://www.freecodecamp.org/news/content/images/2021/02/ship-analogy.png)

![](https://www.codeproject.com/KB/Articles/1207118/30.jpg)