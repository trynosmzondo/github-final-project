# Contributing
All contributions, bug reports, bug fixes, documentation improvements, enhancements, and ideas are welcome.
When contributing a major change to this repository, please first discuss the
change you wish to make via an [issue](contributing/ISSUES.md) or via
[Slack in the #racial-justice-legit-info 
channel](https://callforcode.slack.com/archives/C01CRAN53CM) in the [Call for
Code Slack workspace](https://callforcode.org/slack). Minor issues can simply
be addressed by sending by a pull request.

All [pull requests](contributing/PULL-REQUESTS.md) will require you to ensure
the change is certified via the [Developer Certificate of Origin 
(DCO)](https://github.com/apps/dco/). The DCO is a lightweight way for 
contributors to certify that they wrote or otherwise have the right to submit
the code they are contributing to the project.

Please note we have a [Code of Conduct](#code-of-conduct), please follow it in
all your interactions with the project and its community.

## Coding Standards

This project adheres to the PEP 8 Python Coding Style Guidelines, Django naming
conventions, and other standards.  See [STYLE.md](docs/STYLE.md) for details.

## Programming Languages

Scripts are written for "bash" shell.
Python code is written at the [Python 3.6](https://docs.python.org/3.6/) level.

## Managing Dependencies

Install or uninstall all dependencies using these commands while you are
in the pipenv shell:

```console
(cfc) $ pipenv install <program>"
(cfc) $ pipenv lock -r > requirements.txt"
```

The pipfile, pipfile.lock and requirements.txt will be part of the git
commit/pull-request to be reviewed.


## Pull Request Process

1. Fork the repository.
2. Commit your changes to your fork.
3. Submit a pull request. _Don't forget to add yourself in the [Authors](Authors) file!_
4. Handle any feedback before the request is merged.
5. Accept our sincere Thank You!

