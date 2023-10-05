# eWaterCycle plugin for HYPE hydrological model

HYPE documentation at http://www.smhi.net/hype/wiki/doku.php .

## Installation
Install this package alongside your eWaterCycle installation

```console
pip install ewatercycle-hype
```

Then Hype becomes available as one of the eWaterCycle models

```python
from ewatercycle.models import Hype
```

## Usage

Usage of HYPE forcing generation and model execution is show in 
[docs/generate_forcing.ipynb](https://github.com/eWaterCycle/ewatercycle-hype/tree/main/docs/generate_forcing.ipynb) and [docs/model.ipynb](https://github.com/eWaterCycle/ewatercycle-hype/tree/main/docs/model.ipynb) respectively.

## License

`ewatercycle-hype` is distributed under the terms of the [Apache-2.0](https://spdx.org/licenses/Apache-2.0.html) license.
