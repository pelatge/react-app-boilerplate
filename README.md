# About

This is a React app boilerplate likes create-react-app but simpler and smaller.

I find the create-react-app is quite large so I made this simple one.

**BUT**

❗❗❗ This boilerplate has a HUGE problem: it cannot handle the routes correctly, here's [why](https://stackoverflow.com/questions/27928372/react-router-urls-dont-work-when-refreshing-or-writing-manually).

if any error,please take note;
1.npm install --save-dev @babel/plugin-syntax-jsx @babel/preset-react
2.create .babelrc and fill like below:
  {
    "presets": [
        "@babel/preset-env",
        "@babel/preset-react"
    ]
}
