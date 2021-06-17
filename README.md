# Create-React-App & Tailwind Starter

This is just a simple starter for Create React App and Tailwind, based on instructions found on the [Tailwind web site](https://tailwindcss.com/docs/guides/create-react-app), but with patches/fixes for a couple of issues I find each time I follow those steps...

There is a problem with an incorrect version of ESLINT, which requires a few steps to fix, so this has been done as part of this starter

There is a problem with installing @craco which is solved by removing package-lock.json/yarn-lock.json and the node_modules directory, and running 'npm install' or 'yarn' to reinstall and rebuild.

In theory, you should be able to just clone/fork this repo then...

``` bash
cd ~/your-project-directory
npm install
# or if you prefer...
yarn
```

Once the node_modules are all installed just run..

``` bash
npm start
# or if you're using yarn..
yarn start
```

You should then be able to view your starter running at [http://localhost:3000/](http://localhost:3000/)
