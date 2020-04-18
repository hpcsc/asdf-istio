# asdf-istio

This is a plugin for [asdf](https://github.com/asdf-vm/asdf) to manage `Istio` installation files.

There's already a asdf plugin to install `istioctl` at [asdf-istioctl](https://github.com/rafik8/asdf-istioctl) but I find it not sufficient for my personal use. Most of the time I want to have not only `istioctl` but also all accompanying YAML files and samples.

## Installation

```
asdf plugin-add istio https://github.com/hpcsc/asdf-istio.git
```

## Usage

Check out the [asdf](https://github.com/asdf-vm/asdf) readme for instructions on how to install and manage versions of Istio releases.

## Credits

[asdf-istioctl](https://github.com/rafik8/asdf-istioctl) for initial inspiration
