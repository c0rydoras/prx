# PRx - navigate between projects

Extracted from https://github.com/C0rydoras/stuffdir-arch/blob/3676e76cd5b0129c66bdcfb46fe76f02d4aa884e/bin/stuff-pr#L1-L12

```bash
prx <part of project name>
```

## Usage

add this to .shellrc
```zsh
export PROJECTS_DIR="$HOME/projects" # or any other path
alias prx='. prx'
```

## TODO
- [ ] bash completion
- [ ] fish completion
- [ ] [cookiecutter](https://github.com/cookiecutter/cookiecutter) integration
