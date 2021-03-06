## v2.1.14
- fix(main): labelColor callback for CustomTooltips  
- chore: update core-js to v3 and .babelrc.js 
- fix(sliders): unexpected string issue, update ion-rangeslider, css
- fix(google-maps): initMap defer

##### dependencies update
- update: `@coreui/coreui-plugin-chartjs-custom-tooltips` to `^1.3.1`
- update: `@coreui/coreui-pro` to `^2.1.14`
- update: `@babel/polyfill` to `^7.4.4`
- update: `bootstrap-daterangepicker` to `^3.0.5`
- update: `chart.js` to `^2.8.0`
- update: `codemirror` to `^5.47.0`
- update: `flag-icon-css` to `^3.3.0`
- update: `fullcalendar` to `~3.10.0`
- update: `ion-rangeslider` to `^2.3.0`
- update: `jquery` to `^3.4.1`
- update: `jquery-validation` to `^1.19.1`
- update: `popper.js` to `^1.15.0`
- update: `select2` to `^4.0.7`
- update: `@babel/cli` to `^7.4.4`
- update: `@babel/core` to `^7.4.5`
- update: `@babel/plugin-proposal-object-rest-spread` to `^7.4.4`
- add: `@babel/plugin-proposal-throw-expressions` to `^7.2.0`
- update: `@babel/preset-env` to `^7.4.5`
- update: `autoprefixer` to `^9.6.0`
- update: `browser-sync` to `^2.26.7`
- update: `clean-css-cli` to `^4.3.0`
- update: `js-beautify` to `^1.10.0`
- update: `nodemon` to `^1.19.1`
- update: `node-sass` to `^4.12.0`
- update: `eslint` to `^5.16.0`
- update: `eslint-plugin-compat` to `^3.1.2`
- update: `stylelint` to `^10.1.0`
- update: `stylelint-config-recommended-scss` to `^3.3.0`
- update: `stylelint-config-standard` to `^18.3.0`
- update: `stylelint-order` to `^3.0.0`
- update: `stylelint-scss` to `^3.8.0`

## v2.1.12
- fix(advanced-forms): broken DateRangePicker layout (v3 css breaking changes)
- refactor(advanced-forms): add SingleDatePicker example
- chore: move .stylelintrc to ./ dir
- fix: form-validation-state missing icons
- fix(basic-forms): add missing form-group
- refactor(fullcalendar): fc v3 layout style tweaks
- chore(build/vendors): removes hash tag from urls in css files 
- refactor(forms): add `autocomplete`
- fix(collapse): add `mb-0` to accordion cards
- update: `@coreui/coreui-pro` to `^2.1.7`
- update: `bootstrap` to `^4.3.1`
- update: `core-js` to `^2.6.5`
- update: `popper.js` to `^1.14.7`
- update: `@babel/cli` to `^7.2.3`
- update: `@babel/core` to `^7.3.3`
- update: `@babel/plugin-proposal-object-rest-spread` to `^7.3.2`
- update: `@babel/preset-env` to `^7.3.1`
- update: `autoprefixer` to `^9.4.8`
- update: `chalk` to `^2.4.2`
- update: `codemirror` to `^5.44.0`
- update: `eslint` to `^5.14.1`
- update: `eslint-plugin-compat` to `^2.7.0`
- update: `flag-icon-css` to `^3.3.0`
- update: `fullcalendar` to `^3.10.0`
- update: `jquery-validation` to `^1.19.0`
- update: `js-beautify` to `^1.8.9`
- update: `nodemon` to `^1.18.10`
- update: `node-sass` to `^4.11.0`
- update: `perfect-scrollbar` to `^1.4.0`
- update: `postcss-cli` to `^6.1.2`
- update: `rimraf` to `^2.6.3`
- update: `stylelint` to `^9.10.1`
- update: `stylelint-scss` to `^3.5.3`
- lock: `ion-rangeslider` to `~2.2.0`

## v2.1.11
- feat(spinners): add bootstrap 4.2 spinners 
- feat(toasts): add bootstrap 4.2 toasts 
- fix(collapse): add `mb-0` to accordion cards 
- refactor(forms): add `autocomplete`
- update: `@coreui/coreui-pro` to `^2.1.6`
- update: `bootstrap` to `^4.2.1`
- update: `core-js` to `^2.6.1`
- update: `perfect-scrollbar` to `^1.4.0`
- update: `popper.js` to `^1.14.6`
- update: `@babel/cli` to `^7.2.3`
- update: `@babel/core` to `^7.2.2`
- update: `@babel/plugin-proposal-object-rest-spread` to `^7.2.0`
- update: `@babel/preset-env` to `^7.2.3`
- update: `autoprefixer` to `^9.4.5`
- update: `chalk` to `^2.4.2`
- update: `eslint` to `^5.12.0`
- update: `js-beautify` to `^1.8.9`
- update: `node-sass` to `^4.11.0`
- update: `nodemon` to `^1.18.9`
- update: `postcss-cli` to `^6.1.1`
- update: `rimraf` to `^2.6.3`
- update: `stylelint` to `^9.9.0`
- update: `stylelint-scss` to `^3.5.0`

## v2.1.10
- fix: update `nodemon` to `1.18.7` (vulnerability removed)
- fix: update `npm-run-all` to `^4.1.5` (vulnerability removed)
- fix(cards): smooth collapse card - thanks @MartijnBastiaansen #378
- fix(header): migrate `.divider` to `.dropdown-divider` - thanks @vanam #406
- chore: build/change-version cleanup
- docs(readme): fix broken hyperlinks to 6 versions
- refactor(modals): buttons margin
- feat(switches): add disabled switch example
- fix(switches): missing an ending semicolon
- fix(switches): add missing `<tr>`
- fix(pug): cross-platform use `path.sep` instead of `/` - thanks @vasilevich
- refactor: brand buttons
- refactor: basic forms add autocomplete
- refactor: invoice buttons add `d-print-none`
- update: `@coreui/coreui-pro` to `^2.1.3`
- update: `chart.js` to `2.7.3`
- update: `core-js` to `2.5.7`
- update: `codemirror` to `5.42.0`
- update: `flag-icon-css` to `3.2.1`
- update: `popper.js` to `^1.14.5`
- update: `simple-line-icons` to `2.4.1`
- update: `@babel/cli` to `^7.1.5`
- update: `@babel/core` to `^7.1.6`
- update: `@babel/preset-env` to `^7.1.6`
- update: `autoprefixer` to `9.3.1`
- update: `browser-sync` to `2.26.3`
- update: `eslint` to `^5.9.0`
- update: `eslint-plugin-compat` to `2.6.3`
- update: `js-beautify` to `1.8.8`
- update: `node-sass` to `4.10.0`
- update: `postcss-cli` to `6.0.1`
- update: `shelljs` to `^0.8.3`
- update: `stylelint` to `^9.8.0`  
- update: `stylelint-order` to `^2.0.0`
- update: `stylelint-scss` to `^3.4.0`

## v2.1.5
- update: `@coreui/coreui-pro` to `2.0.12` fixes some IE11 and `rtl` issues
- update: `@babel/cli` to `7.1.2`
- update: `@babel/core` to `7.1.2`
- update: `eslint to `5.6.1`
- update: `foreach-cli` to `1.8.1`
 
## v2.1.4
- feat(switches): add missing `disabled` switch example
- update: `@coreui/coreui-pro` to `2.0.11` fixes some IE11 and `rtl` issues
- chore: update `babel-eslint` to `10.0.1`
- chore: update `stylelint` to `9.6.0`

## v2.1.3
- feat(basic-forms): add missing `date-input` 
- update: `@coreui/coreui-pro` to `2.0.9`
- update: `codemirror` to `5.40.2`
- update: `flag-icon-css` to `3.2.0`
- update: `jquery-validation`to `1.18.0`
- update: `@babel/cli` to `7.1.0`
- update: `@babel/core` to `7.1.0`
- update: `@babel/preset-env` to `7.1.0`
- update: `eslint` to `5.6.0`
- update: `js-beautify` to `1.8.6`
- update: `stylelint-scss` to `3.3.1`

## v2.1.2
- Update: `@coreui/coreui-pro` to `^2.0.7`
- Update: `bootstrap` to `^4.1.3`
- Update: `codemirror` to `^5.40.0`
- Update: `@babel/cli` to `^7.0.0`
- Update: `@babel/core` to `^7.0.0`
- Update: `@babel/plugin-proposal-object-rest-spread` to `^7.0.0`
- Update: `@babel/preset-env` to `^7.0.0`
- Update: `autoprefixer` to `^9.1.5`
- Update: `babel-eslint` to `^9.0.0`
- Update: `browser-sync` to `^2.24.7`
- Update: `copyfiles` to `^2.1.0`
- Update: `eslint` to `^5.5.0`
- Update: `js-beautify` to `^1.8.4`
- Update: `nodemon` to `^1.18.4`
- Update: `stylelint` to `^9.5.0`

## v2.1.1
- **Feat: Add pug support**
- Update: @coreui/coreui-icons to 0.3.0
- Update: @coreui/coreui to 2.0.3
- Update: perfect-scrollbar to 1.4.0

## v2.1.0
- Update: @babel/cli to 7.0.0-rc.1
- Update: @babel/core to 7.0.0-rc.1
- Update: @babel/plugin-proposal-object-rest-spread to 7.0.0-rc.1
- Update: @babel/preset-env to 7.0.0-rc.1
- Update: autoprefixer to 9.1.1
- Update: babel-eslint to 8.2.6
- Update: bootstrap to 4.1.3
- Update: bootstrap-daterangepicker to 3.0.3
- Update: browser-sync to 2.24.6
- Update: clean-css-cli to 4.2.1
- Update: codemirror to 5.39.2
- Update: cross-env to 5.2.0
- Update: datatables.net-bs4 to 1.10.19
- Update: eslint to 5.3.0
- Update: eslint-plugin-compat to 2.5.1
- Update: node-sass to 4.9.3
- Update: nodemon to 1.18.3
- Update: popper.js to 1.14.4
- Update: postcss-cli to 6.0.0
- Update: shelljs to 0.8.2
- Update: stylelint to 9.4.0
- Update: stylelint-order to 1.0.0
- Update: stylelint-scss to 3.3.0
