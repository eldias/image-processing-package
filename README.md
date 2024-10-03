# package_name

Description. 
The package image-processing-package is used to:
	Processing:
	- Histogram matching;
	- Structure similarity;
	- Resize images.
	Utils:
	- Read image;
	- Save image;
	- Plot image;
	- Plot histogram;
	- Plot result.

O pacote image-processing-package é usado para:
	Processamento:
	- Comparação de histograma;
	- Similaridade de estrutura;
	- Redefinir tamanho da imagem.
	Utilidades:
	- Ler imagem;
	- Salvar imagem;
	- Gerar gráfico de imagem;
	- Gerar gráfico de histograma;
	- Gerar gráfico de resultado.

## Installation

Use the package manager [pip](https://pip.pypa.io/en/stable/) to install image-processing-package.

Use o gerenciador de pacotes [pip](https://pip.pypa.io/en/stable/) para instalar image-processing-package.

```bash
pip install image-processing-package
```

## Usage

```python
from image-processing-package.processing import combination
from image-processing-package.processing import transformation
combination.find_difference(image1, image2)
combination.transfer_histogram(image1, image2)
transformation.resize_image(image, proportion)

from image-processing-package.utils import io
from image-processing-package.utils import plot
io.read_image(path, is_gray = False)
io.save_image(image, path)

plot.plot_image(image)
plot.plot_result(*args)
plot.plot_histogram(image)
```

## Author
eldias

## License
[MIT](https://choosealicense.com/licenses/mit/)