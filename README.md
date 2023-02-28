Small webgl wrapper for generative art. Doesn't use any builders or preprocessors, only JS modules

# FFT

Initialize it. Pass a length of frequency bands you want to analyse:

```
let fft = new FFT(32)
```

And then each frame do

```
let freq = fft.get()
```

To start FFT you need to click the document. Before that `fft.get()` will return zeroes
