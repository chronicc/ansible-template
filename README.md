# Ansible Template

> Template for an Ansible project.

## Usage

### Getting started

- Fork the repository or clone it and update your git remote.
- Update `.gitignore`, `README.md`, `ansible.cfg` and `requirements.yml`.
- Decide if you want to use [mise](https://mise.jdx.dev/) or
    [make](https://www.gnu.org/software/make/) as build system and remove the other.
- Run `mise run install` or `make install` to install the required dependencies.

### Getting a clean state

Run `mise run clean` or `make clean` to remove all installed dependencies. When working
with mise, the virtual environment will be recreated immediately.
