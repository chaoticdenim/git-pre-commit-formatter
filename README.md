# git-pre-commit-formatter
a pre-commit hook to format a specific type of files using a specific formatter

## Usage

1. in `format-pre-commit` change `formatter` and `target_extension` to whatever you'd like to use (ex. `black` and `py` respectively)
2. put `format-pre-commit` into `<your_repo>/.git/hooks` and rename it into `pre-commit`
3. Your commits now trigger the hook which reformats your files prior to committing!
