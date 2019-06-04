# VPIN with Limit Order Book Data to Predict Jumps Induced by Toxic Flow

This is a three-month project during my internship at BMLL Technologies, a financial technology start-up based in London. It is not an open-source project, so I am only allowed to upload the [poster](https://github.com/HermannLiang/bmll-vpin/blob/master/BMLL_intern_academic_poster_Chulin_Liang.pdf). The code is written in Python, mainly developed on Jupyter Notebook and later JupyterLab. Main modules used in project were pandas, numpy, matplotlib, plotly, spark and Amazon EMR cluster.

A limit order book is a record of unexecuted limit orders maintained by the security specialist who works at the exchange. You can dind out more information about limit order book at [Investopedia](https://www.investopedia.com/terms/l/limitorderbook.asp).

Volume-synchronized Probability of INformed trading (VPIN) is the ratio of average unbalanced volume to total volume in a period. The VPIN metric measures the fraction of volume-weighted trade that arises from informed traders as the informed tend to trade on one-side of the market and so their activity leads to unbalanced volume.

The project aims to evaluate the predicitive ability of VPIN in the event of price jump induced by toxic flow. Cumulative returns and [Sharp ratio](https://www.investopedia.com/terms/s/sharperatio.asp) were used as metrics to analyse the effectiveness of VPIN.

Some recommended papers on VPIN research: 

* [FLOW TOXICITY AND VOLATILITY IN A HIGH FREQUENCY WORLD](https://pdfs.semanticscholar.org/d532/37a98342918dac8e228d3e688074f6e605cd.pdf)
* [VPIN and the Flash Crash](https://papers.ssrn.com/sol3/papers.cfm?abstract_id=1881731)
* [Assessing Measures of Order Flow Toxicity via Perfect Trade Classification](http://econ.au.dk/fileadmin/site_files/filer_oekonomi/Working_Papers/CREATES/2013/rp13_43.pdf)
