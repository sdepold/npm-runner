# npm-runner

## Installation

```
# Download the sources
git clone git@github.com:sdepold/npm-runner.git "$HOME/.npm-runner"

# Add this to your shell file (e.g. .zshrc)
# Load npm-runner
[ -s "$HOME/.npm-runner/npm-runner.sh" ] && source "$HOME/.npm-runner/npm-runner.sh"
```

## Benefit

If you have a project that uses e.g. gulp (or any other module that ships a binary file) you can now do 

```
gulp my-task
```

instead of

```
node_modules/.bin/gulp my-task
```
