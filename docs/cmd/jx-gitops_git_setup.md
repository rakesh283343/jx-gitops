## jx-gitops git setup

Sets up git to ensure the git user name and email is setup

### Usage

```
jx-gitops git setup
```

### Synopsis

Sets up git to ensure the git user name and email is setup.
  
This is typically used in a pipeline to ensure git can do commits.

### Examples

  jx-gitops git setup

### Options

```
  -d, --dir string     the directory to run the git push command from
  -e, --email string   the git user email to use if one is not setup
  -h, --help           help for setup
  -n, --name string    the git user name to use if one is not setup
```

### SEE ALSO

* [jx-gitops git](jx-gitops_git.md)	 - Commands for working with Git

###### Auto generated by spf13/cobra on 28-Jul-2020