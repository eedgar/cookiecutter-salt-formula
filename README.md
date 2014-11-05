# cookiecutter-salt-formula

[Cookiecutter](https://github.com/audreyr/cookiecutter) repository for generating saltstack formula repository skeleton.

## Install cookiecutter

- Install cookiecutter: [howto](http://cookiecutter.readthedocs.org/en/latest/installation.html)
- Read about Cookiecutter's [features](https://github.com/audreyr/cookiecutter#features)

## Usage

```bash
cookiecutter https://github.com/mahmoudimus/cookiecutter-slim-berkshelf-vagrant.git
```

This will clone `cookiecutter-salt-formula` in your `~/.cookiecutters` directory.

Once the first clone is done you can simply run:

```bash
cookiecutter ~/.cookiecutters/cookiecutter-salt-formula'
```

### Create a new saltstack formula

```bash
cd ${DIRECTORY_YOU_WISH_TO_CREATE_THE_SALT-FORMULA_IN}
cookiecutter ~/.cookiecutters/cookiecutter-salt-formula
```

Follow the prompts for the win!

### Local configuration

You can also create your own ```cookiecutter``` configuration in ```~/.cookiecutterrc```:

```bash
default_context:
    full_name: "Johnny Bravo"
    email: "johnny.bravo@gmail.com"
    github_username: "johnnybravo"
```

