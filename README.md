

# A Nueral Network library for julia

A simple Feet forward neural netwrok written in julia.

# How to install it

To install this package

```
Pkg.clone("https://github.com/loliverhennigh/NeuNet.jl.git")
```
There other packages required

# A sample of code use

``` 
hidden_layers = [100, 20]
batch_size = 10
data = read_data("test.txt")
nn = create_neural_network(data, hidden_layers, batch_size)  
run_back_propagate(nn, data, 1000, .01)

```

