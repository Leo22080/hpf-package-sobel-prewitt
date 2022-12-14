# high_pass_filters

Description. 
The package high_pass_filters is used to:

	- Prewitt filter
	- Sobel filter
    - Image get, plot

## Installation

Use the package manager [pip](https://pip.pypa.io/en/stable/) to install high_pass_filters

```bash
pip install high_pass_filters
```

## Usage

```python
from high_pass_filters.fsobel import sobel
from high_pass_filters.fprewitt import prewit
from high_pass_filters.image import get_image, plot_image

image = get_image(path)
plot_image(image)
plot_image(sobel(image))
plot_image(prewit(image))
```

## Author
Leonardo Costa

## License
[MIT](https://choosealicense.com/licenses/mit/)