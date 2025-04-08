# Regional Indicator Symbols

[Wikipedia](https://en.wikipedia.org/wiki/Regional_indicator_symbol) provides a convenient table of flag emoji. 
This repo has a simple copy in csv format. It looks like this:

```text
flag, code, region
🇦🇨, AC, Ascension Island
🇦🇩, AD, Andorra
🇦🇪, AE, United Arab Emirates
...
🇿🇦, ZA, South Africa
🇿🇲, ZM, Zambia
🇿🇼, ZW, Zimbabwe
```
Access from Python:
```python
import pandas as pd
df = pd.read_csv('https://raw.githubusercontent.com/chrishinds/regional-indicator-symbols/refs/heads/main/regional-indicator-symbols.csv')
```
