# M2_SCE_NeuroComp_Dec

## Using Jupyter notebook on Linux (instead colab)

```bash
# Create and activate virtual environnement
mkdir .venv
python3 -m venv .venv
source .venv/bin/activate

# Install Jupyter
pip install jupyter

# Launch Jupyter
.venv/bin/jupyter-notebook

```

Instead install Brian directly in the notebook, use a requirements.txt file to install good dependencies

```python
%pip install -r requirements.txt
```

After running this previous command, consider to restart the Python kernel in Jupyter notebook

