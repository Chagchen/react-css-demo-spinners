# react-css-demo-spinners

Small React library for CSS spinners

It seems to be a bug in the current version of prettier-eslint cli. In order to run it well, use the following command in the terminal:
" npx prettier-eslint \$PWD/'\*_/_.js' "

If running lint for .js, .jsx file extentions add to package.json "scripts" the following to lint and fix:
"lint": "prettier-eslint --write $PWD/'src/**/*.[jt]s?(x)' && eslint",
"lint:fix": "prettier-eslint --write $PWD/'src/\*_/_.[jt]s?(x)' && eslint --fix ."
