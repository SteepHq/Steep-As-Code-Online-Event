# Steep as Code

This repository accompanies an online event on **Steep as Code**: managing your
[Steep](https://steep.app) metrics as version-controlled code instead of
configuring them in the UI.

It contains the code we generate together during the session.

## What's in here

```
src/
  modules/    Steep module definitions (YAML) — metrics, dimensions, and data sources
```

Each YAML file under `src/modules/` defines a Steep module: the data source it
reads from, the metrics it exposes, and how they can be sliced.

## Reference

Everything in this repo follows the official Steep documentation:

- [Code reference](https://help.steep.app/setup-and-manage/code-reference)
