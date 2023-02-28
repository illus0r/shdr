Small webgl wrapper for generative art. Doesn't use any builders or preprocessors, only JS modules

# FFT

Initialize it:

```
let numberOfBands = 32
let fft = new FFT(numberOfBands)
```

And then each frame do

```
let freq = fft.get()
```

To start FFT you need to click the document. Before that `fft.get()` will return zeroes
