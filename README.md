# bento-report

[![r2c community slack](https://img.shields.io/badge/r2c_slack-join-brightgreen?style=for-the-badge&logo=slack&labelColor=4A154B)](https://join.slack.com/t/r2c-community/shared_invite/enQtNjU0NDYzMjAwODY4LWE3NTg1MGNhYTAwMzk5ZGRhMjQ2MzVhNGJiZjI1ZWQ0NjQ2YWI4ZGY3OGViMGJjNzA4ODQ3MjEzOWExNjZlNTA)

This script configures [Bento](https://github.com/returntocorp/bento)
for commonly used security reporting setups.

## Usage

To start, download the `setup-bento-report` script.
It's recommended to save it to `/usr/local/bin` or similar,
so that it's always in your `PATH`.

Once you have the script, just run

```
$ setup-bento-report
```

to fetch the default security reporting configuration.
You can select an alternative one by specifying its name:

```
$ setup-bento-report --config django
```

or if its your own local config template, its path:

```
$ setup-bento-report --config ~/.bento-report-configs/lukes-special-edition-bento
```

Assuming that the provided directory looks like this:

```
~/.bento-report-configs
└── lukes-special-edition-bento
    ├── .bentoignore
    └── config.yml
```

## Contributing

See [CONTRIBUTING.md](CONTRIBUTING.md)
