<div align="center">

# asdf-skopeo [![Build](https://github.com/zdzielinski/asdf-skopeo/actions/workflows/build.yml/badge.svg)](https://github.com/zdzielinski/asdf-skopeo/actions/workflows/build.yml) [![Lint](https://github.com/zdzielinski/asdf-skopeo/actions/workflows/lint.yml/badge.svg)](https://github.com/zdzielinski/asdf-skopeo/actions/workflows/lint.yml)

[skopeo](https://github.com/zdzielinski/skopeo) plugin for the [asdf version manager](https://asdf-vm.com).

</div>

# Contents

- [Dependencies](#dependencies)
- [Install](#install)
- [Contributing](#contributing)
- [License](#license)

# Dependencies

**TODO: adapt this section**

- `bash`, `curl`, `tar`, and [POSIX utilities](https://pubs.opengroup.org/onlinepubs/9699919799/idx/utilities.html).
- `SOME_ENV_VAR`: set this environment variable in your shell config to load the correct version of tool x.

```bash
# Fedora:
sudo dnf install gpgme-devel libassuan-devel btrfs-progs-devel
```

```bash
# Ubuntu (`libbtrfs-dev` requires Ubuntu 18.10 and above):
sudo apt install libgpgme-dev libassuan-dev libbtrfs-dev pkg-config
```

```bash
# macOS:
brew install gpgme
```

```bash
# openSUSE:
sudo zypper install libgpgme-devel libbtrfs-devel glib2-devel
```

```bash
# Arch Linux:
sudo pacman -S base-devel gpgme btrfs-progs
```

# Install

Plugin:

```shell
asdf plugin add skopeo
# or
asdf plugin add skopeo https://github.com/zdzielinski/asdf-skopeo.git
```

skopeo:

```shell
# Show all installable versions
asdf list-all skopeo

# Install specific version
asdf install skopeo latest

# Set a version globally (on your ~/.tool-versions file)
asdf global skopeo latest

# Now skopeo commands are available
skopeo --version
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/zdzielinski/asdf-skopeo/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [Zachariah Dzielinski](https://github.com/zdzielinski/)
