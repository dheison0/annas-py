# annas-py

Anna's Archive unofficial client library based on web scrapping

## Usage

Install by running:

```bash
pip install annas-py
```

Usage example:

```python
import annas_py
from annas_py.models.args import Language
from pprint import pprint

results = annas_py.search("python", language=Language.EN)
information = annas_py.get_information(results[0].id)
pprint(information)
```
