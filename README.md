# poe-loot-gen
Loot Filter Generator for Path of Exile

This set of script downloads the latest prices for unique items 
and divination cards from poe.ninja and fills out a loot filter 
template based on those.

### Requirements
Python 3.5+

### Usage:
To get up-to-date filter rules for Legacy league:
`python3 -m uniques Legacy`
`python3 -m divcards Legacy`

The filter rules will be written to standard output, i.e. your 
console window. Copy them by hand into your respective loot filter
file.

