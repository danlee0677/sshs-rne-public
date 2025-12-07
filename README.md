# Solving NLOS via HHL & QSVT

## Libraries

- python 3.11.14
- qiskit 2.2.3
- qiskit-aer 0.17.2
- numpy 2.3.5
- pyqsp 0.2.0
- matplotlib 3.10.7
- koreanize_matplotlib 0.1.1

## HHL.ipynb

- Implementation of HHL via `qiskit`
- Uses HHL to solve $Ax=b$ linear system
- NLOS position recovered by Hadamard test

## HHL_visualization.ipynb

- code for visualization(graphs, circuits, etc..)
- requires qcircuit.sty for latex circuit

## QSVT.ipynb

- Implementation of QSVT via `numpy`
- Available also in `qiskit`
- Uses QSVT to solve $Ax=b$ linear system