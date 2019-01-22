Unorganized personal Pd abstractions.
Likely oriented toward ambient, granular/spectral processing, sampling, etc.

# List of objects

## Control
- `flooper`: loop a stream of numbers
- `icounter`: counter with settable interval
- `listaccum`: build a list element by element
- `pd~soundfiler`: `soundfiler` wrapper for use inside `pd~`, turns subprocess DSP off when loading file and back on when finished loading, so as to avoid audio dropouts in the parent patch
- `recsplit`: recursively split a list

## Audio
- `vgrain~`: buffer granulator subunit

# Dependencies

- cyclone
- else
