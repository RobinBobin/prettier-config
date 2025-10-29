# Installation

Install the following packages:

    pnpm i --save-dev prettier@^3.6.2

# Config files

## .prettierignore / .prettierrc.json

A script invoked during `postinstall` copies sample Prettier config files to your project root dir. You can copy them manually if you don't want to let `postinstall` execute:

    cp node_modules/@robinbobin/prettier-config/.prettierignore node_modules/@robinbobin/prettier-config/.prettierrc.json .
