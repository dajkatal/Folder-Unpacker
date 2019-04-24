# Folder-Unpacker
A simple python program that extracts all the files from a directory. (Not including folders)
* Useful when dealing with a directory with several sub-directories.

## Installation

Use the package manager [pip](https://pip.pypa.io/en/stable/) to install foobar.

```bash
pip install unpacker
```

## Usage

```python
from unpacker import FileUnpack

files_init = FileUnpack(input_path, output_path) # Initializes the unpacker
files_init.unpack() # Imports all the files in the input dir into the output dir
```

## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

Please make sure to update tests as appropriate.

## License
[MIT](https://choosealicense.com/licenses/mit/)
