# Using bento-registry

bento-registry allows you to run custom- and r2c-developed check registries
created on sgrep.live.

## Installation

To install, run:
```bash
$ curl -Lo /usr/local/bin/bento-registry https://raw.githubusercontent.com/returntocorp/bento-report/master/bento-registry
$ chmod +x /usr/local/bin/bento-registry
```

## Usage

### r2c registry

To run against an r2c registry, run:

```bash
$ bento-registry r/<registry>
```

from a directory.

For example:

```bash
$ bento-registry r/r2c.python.flask
```

### custom checks

To run using a custom check pack, use the last three characters of a share link on sgrep.live and run:

```bash
$ bento-registry <share>
```

For example:

```bash
$ bento-registry qXn
```
