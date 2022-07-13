[<img src="https://assets.signaloid.io/add-to-signaloid-cloud-logo-dark-v6.png#gh-dark-mode-only" alt="[Add to signaloid.io]" height="30">](https://signaloid.io/repositories?connect=https://github.com/signaloid/Signaloid-Demo-Basic-FPbenchHerbie#gh-dark-mode-only)
[<img src="https://assets.signaloid.io/add-to-signaloid-cloud-logo-light-v6.png#gh-light-mode-only" alt="[Add to signaloid.io]" height="30">](https://signaloid.io/repositories?connect=https://github.com/signaloid/Signaloid-Demo-Basic-FPbenchHerbie#gh-light-mode-only)

# MICRO Benchmark: `fpbench-herbie`

Benchmark from Tsoutsouras et al. MICRO paper.[^0]

The benchmark contains numerical kernels from real-world application.
The numerical kernels comes from FPbench[^1].


## Arguments

```
fpbench-herbie <folder>
	<folder> where the inputs are located (optional, default is "test")
```

## Inputs

The samples are stored in a text file.
The first line of the file is the number of samples that follow.

[^0]: Vasileios Tsoutsouras, Orestis Kaparounakis, Bilgesu Arif Bilgin, Chatura Samarakoon, James Timothy Meech, Jan Heck, Phillip Stanley-Marbell: The Laplace Microarchitecture for Tracking Data Uncertainty and Its Implementation in a RISC-V Processor. MICRO 2021: 1254-1269

[^1]: Nasrine Damouche, Matthieu Martel, Pavel Panchekha, Jason Qiu, Alex Sanchez-Stern, Zachary Tatlock: Toward a Standard Benchmark Format and Suite for Floating-Point Analysis. NSV'16, 2016.
