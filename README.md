# asdf-julia

![CI](https://github.com/lassepe/asdf-julia/workflows/CI/badge.svg)

Julia plugin for asdf version manager

## Install

```bash
asdf plugin-add julia https://github.com/rkyleg/asdf-julia.git
```

## Usage

Check [asdf](ashttps://github.com/asdf-vm/asdfdf) readme for instructions on how to install & manage versions of Julia.

## Release Notes

### v1.1.0

- re-factored install script
- fixed GitHub CI actions (currently only testing for Linux-x64 and Mac OS)
- handle different architectures and support freeBSD
- support installing nightly builds with `asdf install julia nightly`
