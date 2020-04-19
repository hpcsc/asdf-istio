# asdf-istio

This is a plugin for [asdf](https://github.com/asdf-vm/asdf) to manage `Istio` installation files.

There's already a asdf plugin to install `istioctl` at [asdf-istioctl](https://github.com/rafik8/asdf-istioctl) but I find it not sufficient for my personal use. Most of the time I want to have not only `istioctl` but also all accompanying YAML files and samples.

## Installation

```
asdf plugin-add istio https://github.com/hpcsc/asdf-istio.git
```

## Usage

Check out the [asdf](https://github.com/asdf-vm/asdf) readme for general usage of asdf.

Most common usage:

```
asdf list-all istio # to list available versions of Istio installation files
asdf install istio [latest|x.y.z] # to get latest|x.y.z version of Istio installation files
asdf global istio x.y.z # set version x.y.z as global
```

This plugin downloads Istio installation files (including YAML files, samples) into asdf predefined location. To check where is that location:

```
asdf where istio
```

## Credits

[asdf-istioctl](https://github.com/rafik8/asdf-istioctl) for initial inspiration
