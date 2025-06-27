This project is a tiny autograd engine that implements backpropagation over a dynamically built DAG and a small neural networks library on top of it with a PyTorch-like API.

To run the tests, you will have to install PyTorch, which the tests use as a reference for verifying the correctness of the calculated gradients. Then simply run `python -m pytest`
