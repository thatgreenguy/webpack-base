# webpack-base

Webpack 4 base setup - useful starting point to build web projects not utilising a front-end framework such as Vue, React et al.

Provides:

- Babel Compiler/Transpiler converting modern Javascript to safer older version for deployment.
- Javascript uglification and minification in production mode
- CSS merging and minification in production mode
- Asset handling

This can be extended to do more, I'm sure, but the aim was to provide a solid, working starting point.

Webpack configuration is nicely divided between dev and production with both configs sharing a common base - see the build directory.

`npm run dev`

Runs webpack dev server locally - Project is running at http://localhost:8080/ without any css or js optimisations.

`npm run build`

Clears the dist directory and rebuilds with the css and js optimisations ready for deployment.


Thanks to Tero Auralinna for his great article: https://auralinna.blog/post/2018/setting-up-webpack-4-for-a-project

Webpack: https://webpack.js.org/
