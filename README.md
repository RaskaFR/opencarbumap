# opencarbumap

This is a map of french gas station. The color of markers depends of prices.
There is one layer per fuel.

Data come from french government open data: https://www.prix-carburants.gouv.fr/rubrique/opendata/.
This project use the daily (*jour*) file.

## Install

```bash
./download_data.sh
python read.py
firefox map.html
```
