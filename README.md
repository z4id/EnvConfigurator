# EnvConfigurator
## _Python's Last Environment Handler, Ever_

[![N|Solid](https://www.python.org/static/img/python-logo.png)](https://www.python.org/)

EnvConfigurator is a Python package aimed towrds handling environment in two 
lines of code while running any Python application.

## Features

- Load and set .env file for you.
- Parse and get environment variable as per your criteria.
- Criteria can include var_type, optional, choices, custom message and 
  default value.
- Import and Use in just 3 lines of code.
- Access your Environment Variable with . (dot)

## Tech

- [Python] - Python

And of course EnvConfigurator itself is open source with a [public repository][envconfigurator]
 on GitHub.

## Installation

EnvConfigurator requires [Python3](https://pypi.org/) to run.

```sh
pip install EnvConfigurator
```

## Usage

```sh
from EnvConfigurator import EnvVar, EnvParser

env_vars = [
        EnvVar("DB_NAME", str),
]

parsed_env = EnvParser(env_vars).all

# Access your environment variable with dot notation
print(parsed_env.DB_NAME)
```

## Development

Want to contribute? Great!

Fork Gihub repository and create a Pull Request.

Run tests before submitting the request
```sh
python manage.py test
```

## License

MIT

**Free Software, Hell Yeah!**

[//]: # (These are reference links used in the body of this note and get stripped out when the markdown processor does its job. There is no need to format nicely because it shouldn't be seen. Thanks SO - http://stackoverflow.com/questions/4823468/store-comments-in-markdown-syntax)

   [envconfigurator]: <https://github.com/z4id/z4id>
   [git-repo-url]: <https://github.com/z4id/>
   [@z_4id]: <http://twitter.com/z_4id>
