Start working with the design system
1. Install Dependency
```
npm install
```

2. Run on development 
```
npm run watch
```
3. Build for production
```
npm run build
```
## File Structure
Within the download you'll find the following directories and files, logically grouping common assets and providing both compiled and minified variations. You'll see something like this:
```
github/hope-ui-admin-dashboard/
  dist
    ├── assets
    │    ├── css
    │    ├── images
    │    ├── js
    │    └── vendor
    ├── dashboard
    │    └── all html pages on folder based
    └── index.html
  src
    ├── assets
    │    ├── images
    │    │    ├── icon.png
    │    │    ├── favicon.ico
    │    │    └── loader.gif
    │    ├── js
    │    │    ├── hope-ui.js
    |    │    └── plugins
    |    │         ├── slider-tabs.js
    |    │         ├── countdown.js
    |    |         └── prism.min.js
    │    └── scss
    │        ├── bootstrap/
    │        │     ├── forms/
    │        │     ├── helper/
    │        │     ├── mixins/
    │        │     ├── utilites/
    │        │     └── vendor/
    │        ├── custom
    │        │     ├── auth/
    │        │     ├── kanban/
    │        │     ├── pricing/
    │        │     └── ui-kit/
    |        ├──customizer
    │        │     ├── components/
    │        │     ├── layout/
    │        │     ├── menu-style/
    │        │     ├── utillities/
    │        │     ├── components.scss
    │        │     ├── dark.scss
    │        │     ├── root.scss
    │        │     └── variables.scss
    │        ├── hope-ui-design-system
    │        │     ├── components/
    │        │     ├── helper/
    │        │     ├── layout-style/
    │        │     ├── pages/
    │        │     ├── plugins/
    │        │     ├── variables/
    │        │     └── variables.scss
    │        ├── dark
    │        │     ├── components/
    │        │     ├── helper/
    │        │     ├── layout-style/
    │        │     ├── pages/
    │        │     ├── plugins/
    │        │     ├── reboot/
    │        │     ├── _dark.scss
    │        │     └── _index.scss
    │        ├── rtl
    │        │     ├── components/
    │        │     ├── pages/
    │        │     ├── reboot/
    │        │     ├── utilities/
    │        │     └── _index.scss
    │        ├── rtl.scss
    │        ├── dark.scss
    │        ├── custom.scss
    |        ├── customizer.scss
    │        └── hope-ui.scss
    ├── templates
    |    ├── layouts
    │    |    ├── boxed-fancy
    │    |    ├── boxed
    │    |    ├── default
    │    |    ├── dual-compact
    │    |    ├── dual-horizontal
    │    |    ├── horizontal
    |    │    └── simple
    |    ├── pages
    |    │    ├── all folders based files
    |    │    └── index.hbs
    |    └── partials
    |        ├── components/
    |        └── all files based on hbs file in design system
    ├── gulp
    │    └── all gulp task here
    ├── .gitignore
    ├── gulp.config.json
    ├── gulpfile.js
    ├── LICENSE
    ├── README.md
    └── package.json
```

## Browser Support
![chrome](https://assets.iqonic.design/hope-ui/github/chrome.png)
![Firefox](https://assets.iqonic.design/hope-ui/github/Firefox.png)
![Safari](https://assets.iqonic.design/hope-ui/github/Safari.png)
![Microsoft](https://assets.iqonic.design/hope-ui/github/Microsoft%20edge.png)
![Operamini](https://assets.iqonic.design/hope-ui/github/Operamini.png)
