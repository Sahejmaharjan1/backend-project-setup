steps:

1. touch .gitignore file
2. yarn init
3. node -v > .nvmrc (creates a node version and store in .nvmrc file)
4. npx tsc --init (creates a tsconfig.json file)
5. yarn add -D eslint (add eslint as dev dependencies to use eslint in the project)
6. npx eslint --init (use airbnb style guide) creates eslintrc.js file
   this might create a package-lock.json file if you are using remove package-lock file
7. touch .eslintignore (ignore eslint in specified files)
8. yarn add -D prettier
9. touch .prettierrc
10. yarn add -D eslint-plugin-prettier eslint-config-prettier (helps to play around with eslint and prettier)
11. yarn add -D eslint-import-resolver-typescript tsconfig-paths (helps in resolving path with eslint)
12. customize .eslintrc file as we have installed different plugins to work with it
