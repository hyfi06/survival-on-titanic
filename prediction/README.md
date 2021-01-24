# Prediction

## Install

### Virtual environment

Create environment

```bash
python3 -m venv venv
```

Initialization environment

```bash
source venv/bin/activate
```

### Install dependencies

```bash
pip3 install -r requirements.txt
```

### Crate Kernel ipython

```bash
ipython kernel install --user --name=survival-on-titanic
```

## Run

```bash
source venv/bin/activate
jupyter nbextension enable --py widgetsnbextension --sys-prefix
jupyter nbextension enable --py jupyter_tabnine --sys-prefix
jupyter-notebook &
```

Select `survival-on-titanic` kernel
