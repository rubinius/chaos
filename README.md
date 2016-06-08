# Chaos

Chaos is a multi-threaded, multi-process, highly parallel application exhibiting heavy object allocation, IO, and CPU-bound workloads. Chaos is an instrument to aid in testing and evaluating highly parallel system architectures.

The following components are essential elements of the chaos application:

1. Parallelism
1. Processes
1. Logging
1. Communication
1. Entropy
1. Asymmetry
1. Allocation
1. Finalization
1. CPU-bound workloads
1. IO-bound workloads
1. FFI
1. C-API

Chaos is presently written in Ruby, but no guarantees are made that it will continue to be written in Ruby.


## Invoking Chaos

```
$ git clone https://github.com/rubinius/chaos
$ cd chaos
$ # Select desired Rubinius version
$ rbx chaos
```


## Code of Conduct

Participation in this project is governed by the Rubinius [Code of Conduct](http://rubinius.com/code-of-conduct/).


## License

This project uses MPL-2.0. See the LICENSE file for details.
