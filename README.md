# cvtgif

## Table of Contents

- [Description](#description)
- [Installation](#installation)
- [Quick start](#quick-start)
- [Features](#features)

## Description

Converts images into gif file

## Installation

Download using pip via pypi.

```bash
$ pip install cvtgif_test --upgrade
  or
$ pip install git+https://github.com/LouisKimDev/cvtgif_test.git
```

(Mac/homebrew users may need to use `pip3`)

## Quick start

```python
 >>> from cvtgift_test.converter import GifConverter
 >>> c = GifConverter("your original images path", 'your gif output path', (320,240))
 >>> c.convert_gif()
```

## Features

- Python library to convert single order multiple frame gif images
- OpenCV does not support gif images.
