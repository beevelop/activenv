# activenv


## Installation
```
basher install beevelop/activenv
```

## Notes
### OS X
Install Bash 4 before using activenv
```
brew install bash
```

## Use Case
1. Define the required ENVs in a meta file
2. Run `activenv` and set required ENVs interactively
    - Validate the input with simple regex
3. Substitute ENVs in a template file and write it to the file system
    - like `envsubst`
4. e.g. run `docker-compose`
