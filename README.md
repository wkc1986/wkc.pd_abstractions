Unorganized personal Pd abstractions.
Likely oriented toward ambient, granular/spectral processing, sampling, etc.

# List of objects

- `gloop~`: buffer granulator component
- `hann-win`: creates a Hann window with name `$1` and size `$2` using the [method from the Pd tutorial](http://pd-tutorial.com/english/ch03s08.html)
- `lgrain~`: buffer granulator component triggered with a list of argument-value pairs
- `ofWaveform~`: attempt at analog of Max's `waveform~` using Ofelia
- `recsplit`: recursively split a list
- `specdelay~`: spectral delay with GUI arrays for controlling amplitude and delay time. Largely taken from [Pd Tutorial](http://www.pd-tutorial.com/english/ch03s08.html)
- `specter~`: spectral blurrer

# Dependencies

- cyclone
- else
- ofelia
