# pipeline-examples
Example Github and AzDO YAML pipeplines

## GitHub

### Jobs
- Can pass variables to other jobs using `outputs` and echoing data to `$GITHUB_OUTPUT`
- Can share `env` variables across steps

### Steps
- Can share variable across steps using `$GITHUB_ENV`
