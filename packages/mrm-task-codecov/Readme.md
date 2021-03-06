# mrm-task-codecov

[Mrm](https://github.com/sapegin/mrm) task that adds [Codecov](https://codecov.io/) to Travis CI config (see [travis](../travis) task) and a Readme badge.

## Usage

```
npm install -g mrm mrm-task-codecov
mrm codecov
```

## Options

See [Mrm docs](https://github.com/sapegin/mrm#usage) for more details.

### `readmeFile` (default: `Readme.md`)

Name of the Readme file.

### `github` (default: extracted from `.git/config` file)

Your GitHub user name.

## Change log

The change log can be found in [Changelog.md](Changelog.md).

## Contributing

Everyone is welcome to contribute. Please take a moment to review the [contributing guidelines](../../Contributing.md).

## Authors and license

[Artem Sapegin](http://sapegin.me) and [contributors](https://github.com/sapegin/mrm-tasks/graphs/contributors).

MIT License, see the included [License.md](License.md) file.
