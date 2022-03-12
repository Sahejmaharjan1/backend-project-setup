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
13. yarn add nodemon
14. touch nodemon.json (custom configuration)
15. yarn add dotenv-safe
16. yarn add -D @types/dotenv-safe
17. touch .env.example
18. touch .env
19. dotenv.config() in src/index.ts file
