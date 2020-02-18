# .githooks

### Track your git hooks as part of your git repository (and opt into running them)

On many projects, branch naming conventions can start to become more and more necessary.  A decent solution to this is to create pre-commit hooks that contributors can utilize to keep themselves following a shared convention.  One of the problems with this approach is that git hooks are not persisted as part of the repository which means that they can exist in different versions on different person's workstations.  This can lead to maintenance annoyances, but can be easily rectified by tracking these hooks as part of the repository.  This repository serves as an example of how one might set that system up.


### Usage
To activate the .githooks directory:

    .githooks/install


To deactivate the .githooks directory:

    .githooks/uninstall

    
