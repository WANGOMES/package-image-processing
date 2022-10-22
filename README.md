# Package Image Processing

Description. 
The package image_processing is used to:

Processing:
- Histogram matching 
- Strutural Similarity
- Resize image

Utils:
- Read image
- Save image
- Plot image
- Plot result
- Plot histogram

## Installation

Use the package manager [pip](https://pip.pypa.io/en/stable/) to install package_name

```bash
pip install image_processing
```

## Usage

### In Processing

```python
from image_processing.processing import combination
combination.find_difference(image1, image2) 
#Strutural Similarity.
```
```python
from image_processing.processing import combination
combination.transfer_histogram(image1, image2) 
#Histogram matching.
```
```python
from image_processing.processing import transformation
transformation.resize_image(image, proportion)
#Resize image.
```
____________________________________________________________
### In Utils
```python
from image_processing.utils import io
io.read_image(path) 
#Read image.
```
```python
from image_processing.utils import io
io.save_image(image, path) 
#Save image.
```
```python
from image_processing.utils import plot
plot.plot_image(image) 
#Plot image.
```
```python
from image_processing.utils import plot
plot.plt_result(args) 
#Plot result.
```
```python
from image_processing.utils import plot
plot.plot_histogram(image)
#Plot histogram.
```


## Author
Wanderson Gomes

## License
[MIT](https://choosealicense.com/licenses/mit/)
