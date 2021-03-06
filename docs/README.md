# [PyRoss Documentation](https://pyross.readthedocs.io/en/latest/)

## Worked out examples

* [**Example: Deterministic sampling in PyRoss**](https://github.com/rajeshrinet/pyross/blob/master/examples/deterministic/ex01-SIR.ipynb)
* [**Example: Stochastic sampling in PyRoss**](https://github.com/rajeshrinet/pyross/blob/master/examples/stochastic/ex1-SIR.ipynb)
* [**Example: Inference in PyRoss**](https://github.com/rajeshrinet/pyross/blob/master/examples/inference/ex01_inference_SIR.ipynb)
* [**Example: Inference with latent variables in PyRoss**](https://github.com/rajeshrinet/pyross/blob/master/examples/inference/ex05_inference_latent_SIR.ipynb)
* [**Example: Simulate any generic compartmental model in PyRoss**](https://github.com/rajeshrinet/pyross/blob/master/examples/deterministic/ex16-Spp.ipynb)
* [**Example: Inference with any generic compartment model in PyRoss**](https://github.com/rajeshrinet/pyross/blob/master/examples/inference/ex_Spp.ipynb)
* [**Example: Computing the evidence and comparing models in PyRoss**](https://github.com/rajeshrinet/pyross/blob/master/examples/inference/ex-evidence.ipynb)


In addition please have a look at the [examples folder](https://github.com/rajeshrinet/pyross/tree/master/examples) for more Jupyter notebook examples.
The examples are structured along the following pipeline

![Imagel](../examples/pipeline.jpg)

The examples are classified as:

* [contactMatrix](https://github.com/rajeshrinet/pyross/tree/master/examples/contactMatrix): shows how to use contact matrix and intervention

* [control](https://github.com/rajeshrinet/pyross/tree/master/examples/control): shows how to compute time dependent contact matrix which depend of time and state

* [deterministic](https://github.com/rajeshrinet/pyross/tree/master/examples/deterministic): is for integration of equations of motion in the limit of no stochastic components

* [forecast](https://github.com/rajeshrinet/pyross/tree/master/examples/forecast): is for forecasting once the parameters are known

* [hybrid](https://github.com/rajeshrinet/pyross/tree/master/examples/hybrid): is for integration of equations of motion which can switch from deterministic to stochastic

* [inference](https://github.com/rajeshrinet/pyross/tree/master/examples/inference): shows how to infer parameters and select models given data

* [stochastic](https://github.com/rajeshrinet/pyross/tree/master/examples/stochastic): is for integration of equations of motion with stochastic components


[Models.pdf](https://github.com/rajeshrinet/pyross/blob/master/docs/models.pdf) describes various epidemiological models available in PyRoss (SIR, SIkR, SEIR, SEkIkR, SEAIR, SEAIRQ, etc).
