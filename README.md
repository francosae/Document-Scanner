# Document Scanner with OpenCV


This scanner is built in Python using OpenCV, it takes an image of any document, outlines the corners, and then transforms the image to the appropriate perspective to get a correct view of the document, and applies a color threshold to give it a similar appearance to a scanned image.

### Built With

- [Python](https://www.python.org/)
- [OpenCV](https://opencv.org/)

#### Here are some examples of scanned images.

![Screenshot](example1.png)
![Screenshot](example2.png)
## Installation

Use the package manager [pip](https://pip.pypa.io/en/stable/) to install scikit-image.

```bash
python -m pip install -U scikit-image
```

## Usage

To scan images, you have to input the directory to the image you would like to scan.
```python
python DocuScan.py --images (Directory of Image)
```

## Contributing
Pull requests are welcome.
Please make sure to update tests as appropriate.
