# README

Global configuration for PhpStorm

## Installation

Location of the PhpStorm folder is depending on OS and PhpStorm version. See section [Project and IDE settings](https://www.jetbrains.com/help/phpstorm/project-and-ide-settings.html) for more information about the configuration directory structure.

### Linux

#### Xubuntu

```sh
# Use local installation

git checkout linux/xubuntu
bin/installer install

# Use remote installation

curl --location "https://gitlab.com/mauchede/phpstorm-config/raw/linux/xubuntu/bin/installer" | bash -s -- install
```

__Note__: Make sure PhpStorm is not running, or it will overwrite the changed files before shutting down.

### macOS

#### Darwin

```sh
# Use local installation

git checkout mac-os/darwin
bin/installer install

# Use remote installation

curl --location "https://gitlab.com/mauchede/phpstorm-config/raw/mac-os/darwin/bin/installer" | bash -s -- install
```

__Note__: Make sure PhpStorm is not running, or it will overwrite the changed files before shutting down.

## Contributing

1. Fork it.
2. Create your branch: `git checkout -b feature/my-new-feature`.
3. Commit your changes: `git commit -am 'Add some feature'`.
4. Push to the branch: `git push origin feature/my-new-feature`.
5. Submit a [merge request](https://docs.gitlab.com/ee/user/project/merge_requests/).

__Note__: [GitHub repository](https://github.com/mauchede/phpstorm-config) is a mirror. [Merge request](https://docs.gitlab.com/ee/user/project/merge_requests/) has to be submitted on the [GitLab repository](https://gitlab.com/mauchede/phpstorm-config).

If you like / use this project, please let me known by adding a [★](https://help.github.com/articles/about-stars/) on the [GitHub repository](https://github.com/mauchede/phpstorm-config) or on the [GitLab repository](https://gitlab.com/mauchede/phpstorm-config).

## Credits

The original project has been created by [nicwortel](https://github.com/nicwortel).

## Links

* [project and ide settings](https://www.jetbrains.com/phpstorm/help/project-and-ide-settings.html)
* [nicwortel/phpstorm-ide-config](https://github.com/nicwortel/phpstorm-ide-config)
