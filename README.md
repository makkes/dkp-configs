# Kommander configuration files

This repository holds a set of configuration files for typical deployment scenarios of [DKP Kommander](https://d2iq.com/products/kommander).

## How to use

Some of the configuration files are templated in a way that can easily be used with a combination of `envsubst` and [`direnv`](https://direnv.net/):

1. `cd` into the directory holding the configuration file you want to use.
1. Create an `.envrc` file iholding all variables consumed in the configuration file.
1. Run `envsubst < file.yaml > kommander.yaml`
1. Use the file with the Kommander CLI: `kommander install --config kommander.yaml`
