```
conda create -n qiskit-env python=3.11 -y
conda activate qiskit-env

conda install numpy=1.26 matplotlib ipykernel -y
pip install qiskit qiskit-aer
pip install pylatexenc

python -m ipykernel install --user --name=qiskit-env --display-name="Python (Qiskit)"
```