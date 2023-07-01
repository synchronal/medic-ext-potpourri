# medic-ext-potpourri

An extension pack with a medley of scripts and helpers for [medic-rs](https://github.com/synchronal/medic-rs).

Checks and steps may depend on languages or frameworks being available in the `PATH`.

## Installation

```shell
brew tap synchronal/tap
brew install medic-ext-potpourri
```

Example `Brewfile`:

```shell
tap 'synchronal/tap'

brew  'synchronal/tap/medic'
brew  'synchronal/tap/medic-ext-potpourri'
```

## Scripts

| name                  | dependencies | description |
| --------------------- | ------------ | ----------- |
| `medic-check-hostess` | Elixir       | Checks whether `hostess` has been used to provide host aliases in `/etc/hosts`. |
|                       |              | - host-exists |
|                       |              | - installed   |
| `medic-check-phoenix` | Elixir       | Checks whether Phoenix has been set up for development. |
|                       |              | - local-certs |

