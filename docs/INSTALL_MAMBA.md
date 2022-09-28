

In order to get native support for Mac M1 (or other Apple Silicon chips), you have to follow [this](https://developer.apple.com/metal/tensorflow-plugin/) guide.


However, instead of installing `conda`, consider installing `mambaforge`. (for details, checkout [this](https://stackoverflow.com/a/72970797/6390175) answer)

```bash
brew install mambaforge
```

And then later install `mamba` via

```bash
conda install mamba -n base -c conda-forge
```

Now, you can create a new env via

```bash
mamba env create -n machine_learning -f docs/config/tf-metal-arm64.yaml
```
