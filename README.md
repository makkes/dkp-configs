# Kommander configuration files

This repository holds a set of configuration files for typical deployment scenarios of [DKP Kommander](https://d2iq.com/products/kommander).

## How to use

Some of the configuration files are templated in a way that can easily be used with a combination of `envsubst` and [`direnv`](https://direnv.net/):

1. Put an `.envrc` file in the respective configuration file's directory holding all variables consumed in the configuration file.
1. Run `envsubst < file.yaml > /some/where/config.yaml`
