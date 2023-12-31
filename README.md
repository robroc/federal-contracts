# An analysis of Canadian federal contracts

This repo contrains Jupyter notebooks that prepare and analyze data Canadian federal contracts over $10,000, which are [published here](https://search.open.canada.ca/contracts/) ([full data download here](https://open.canada.ca/data/en/dataset/d8f85d91-7dec-4fd1-8055-483b77225d8b)).

This analysis was used in two reports by the Investigative Journalism Foundation:

* [Why do government IT contracts have such huge cost overruns?](https://theijf.org/why-do-government-it-contracts-have-such-huge-cost-overruns)
* [Ottawa spending record amounts outsourcing access to information requests](https://theijf.org/ottawa-spending-record-amounts-outsourcing-access-to-information-requests)

### Descriptions of notebooks

[data_prep.ipynb](data_prep.ipynb) - Loads raw data from government website, cleans up vendor names, standardizes unique procurement IDs, isolates amended contracts.

[amended_contracts_analysis.ipynb](amended_contracts_analysis.ipynb) - Statistical analysis of amended contracts and cost inflation.

### Acknowledgement

Much of the prep code was inspired by the work of [Sean Boots at Carleton University](https://govcanadacontracts.ca/methodology/). For the most part, my Python code is a direct translation of Sean's R code.
