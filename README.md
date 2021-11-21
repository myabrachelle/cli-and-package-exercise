# cli-and-package-exercise
This exercise is open-book/open-web, but please don't get direct assistiance from other people. There's a chance you will not be familiar with every concept in the exercise - this is intentional. The ability to quickly figure things out by searching online is part of what this is evaluating. Every step in this exercise is well documented online, with many examples.

## Tasks
1. Fork this repository
2. Using your preffered JavaScript package manager, install (in a way the includes a lockfile) one of the following: 
  - Typescript
  - Coffeescript
  - PostCSS
  - Sass
3. With the same package manager, install a transpiler (most likely Babel), and any additional packages needed to convert the Typescript/PostCSS/etc to something a browser can read. 
4. Gitignore `node_modules`
5. Create a `src` directory. Add a file using the syntax of the package you installed in step 1 (Typescript, PostCSS, etc). You can just paste something in from an online example. 
6. Create a `dist` directory that will contained the transpiled version of the file in `/src`
7. In `package.json` (which will be present if the prior steps were performed properly), the "[scripts](https://docs.npmjs.com/cli/v8/using-npm/scripts)"  section should include a `build` script for transpiling the file in '/src` to the browser readable one in `/dist`.
8. Run the build script to generate the transpiled file in `/dist`
9. Commit & push your changes and open a pull request to add them to cli-and-package-exercise.

TLDR - create a simple project that transpiles single Typescript, Coffescript, PostCss or Sass file to a browser-understood file. 
