# my-react-boilerplate

```bash
# run create-snowpack-app
npx create-snowpack-app . --template @snowpack/app-template-react-typescript --use-yarn --no-git --force

# fill some information on package.json
yarn init -y

# install eslint
yarn add -D eslint \
            @typescript-eslint/eslint-plugin \
            @typescript-eslint/parser \
            eslint-plugin-simple-import-sort \
            eslint-config-prettier \
            eslint-plugin-prettier

# install lint-staged
yarn add -D lint-staged node-git-hooks

## after setting lint-staged on package.json
yarn install

# install sass plugin for snowpack
yarn add -D @snowpack/plugin-sass

# install stylelint
yarn add -D stylelint \
            stylelint-config-sass-guidelines \
            stylelint-config-order \
            stylelint-config-rational-order \
            stylelint-config-prettier stylelint-prettier
```
