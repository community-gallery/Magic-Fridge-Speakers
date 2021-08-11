# Magic-Fridge-Speakers
Have you ever wanted your favorite song to fill you with joy every time you open your fridge and grab your favorite food? Look no further.
# Usage

Magic-Fridge-Speakers is a Python library for utilizing FreeRTOS to enable a Refriderator to play specific songs upon grabbing certain produce.

## Installation

Use the package manager [pip](https://pip.pypa.io/en/stable/) to install MFS.

```bash
pip install magic-fridge-speakers
```

## Usage

```python
import magic-fridge-speakers as mfs

# sets 'Dancing Queen' to play while grabbing lettuce
mfs.playOnLettuce('Dancing Queen')

# returns decibel level
mfs.volume('veryLoud')

# returns frequency
mfs.bass('earthquake')
```

## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

Please make sure to update tests as appropriate.

## License
[MIT](https://choosealicense.com/licenses/mit/)
