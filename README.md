[![Open Source Love](https://badges.frapsoft.com/os/v2/open-source.svg?v=103)](https://github.com/TeamSudoCoders/Granite)    [![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](https://opensource.org/licenses/MIT)
# Granite

Granite is a lightweight, pre-trained MobileNet model for detected cracks on concrete walls, slabs, pavements and other stuctures made of concrete. This pre-trained model was created using transfer learning and has a validation accuracy of 99.95 %. The model was trained on the [Concrete Crack Images for Classification](https://data.mendeley.com/datasets/5y9wdsg2zt/1) from Medeley.

Scripts written and trained by Nikhil Raghavendra (@nikhilraghava).

## Pre-requisites

- This repository
- Python 3.6.5
- TensorFlow 1.9.0
- NumPy 1.14.2

## Usage

Clone or download this repository and execute the following command in the terminal with this repository being the current working directory.

```python
python classify.py [path to image — relative to the script]
```

## Tested Operating Systems

- macOS 10.13.6
- macOS 10.14

## License

Licensed under [MIT License](https://github.com/TeamSudoCoders/Granite/blob/master/LICENSE).
