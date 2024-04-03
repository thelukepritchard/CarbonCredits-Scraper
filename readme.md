# Carbon Credits Scraper

This script simply scrapes the site carboncredits.com and extracts the market data

## Usage

```sh
python3 main.py
```

## Requirements

### Install chromedriver

You will need apppropriate chromedriver from
https://googlechromelabs.github.io/chrome-for-testing/#stable

You need to install appropaite chromedriver

You then need to update `driver_path` in the `main.py` to point to this driver

### Install PIP packages

```sh
pip3 install -r requirements.txt
```

## Output 

The following output should look like this:

```txt
lukepritchard@Lukes-MacBook-Air CarbonCredits-Scraper % python3 main.py
European Union: €58.77
UK: £34.33
California: $28.66
Australia (AUD): $33.90
New Zealand (NZD): $59.30
South Korea: $6.09
China: $12.12
Aviation Industry Offset: $0.63
Nature Based Offset: $0.93
Tech Based Offset: $0.65
```

You can then modify this script to use data appropriately 