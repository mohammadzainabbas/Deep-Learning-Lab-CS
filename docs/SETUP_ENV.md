## Create new enviornment 👨🏻‍💻

### Table of contents

- [Create new enviornment](#create-new-env)
  * [Via conda](#new-env-conda)
  * [Via mamba](#new-env-mamba)
  * [Via virtualenv](#new-env-virtualenv)

#

<a id="create-new-env" />

### 1. Create new enviornment

<a id="new-env-conda" />

#### 1.1. Via conda

Before starting further, make sure that you have `conda` (Anaconda) installed (otherwise, create a new env via [virutalenv](#new-env-virtualenv)). We will create a new enviornment for the purpose of our labs:

```bash
conda create -n machine_learning python=3 -y 
```

and activate it

```bash
conda activate machine_learning
```

<a id="new-env-virtualenv" />

#### 1.2. Via virtualenv

You can create your virtual enviornment without conda as well. In order to do that, make sure that you have [`virtualenv`](https://pypi.org/project/virtualenv/) installed or else, you can install it via:


```bash
pip install virtualenv
```

Now, create your new enviornment called `machine_learning`

```bash
virtualenv -p python3 machine_learning
```

and then activate it via

```bash
source machine_learning/bin/activate
```
