# FairlayAPI
Tasks with Fairlay Python APIs

Requirements: Python 3 installed

Tested with Python 3.7.

`run.py` program can display: All of the large open orders (over $5000) placed in those 3 markets: American football / NFL, college football / NCAAF, and basketball / NBA. Currently, the threshold `$5000`, the markets type, and displayed fields are hard-coded.

The currency used by Fairlay is mBTC, this program gets the USD/BTC exchange rate from [Blockchain](https://www.blockchain.com/api/exchange_rates_api) API and convert the threshold `$5000` to mBTC value.

Run the program:
```bash
$ python run.py
Or
$ ./run.py
```
