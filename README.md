The data set can be downloaded from <https://github.com/sibylhe/mmm_stan/blob/main/data.csv>.

## Data

Four years' (209 weeks) records of sales, media impression and media spending at weekly level.

1. Media Variables

> Media Impression (prefix='mdip_'): impressions of 13 media channels: direct mail, insert, newspaper, digital audio, radio, TV, digital video, social media, online display, email, SMS, affiliates, SEM.
Media Spending (prefix='mdsp_'): spending of media channels.

2. Control Variables

> Macro Economy (prefix='me_'): CPI, gas price.
> Markdown (prefix='mrkdn_'): markdown/discount.
> Store Count ('st_ct')
> Retail Holidays (prefix='hldy_'): one-hot encoded.
> Seasonality (prefix='seas_'): month, with Nov and Dec further broken into to weeks. One-hot encoded.
> This repo is a simplified solution of Python/STAN Implementation of Multiplicative Marketing Mix Model <https://github.com/sibylhe/mmm_stan/tree/main>.

EDA, model setup and curve interpretation are included. Details can be found in main.ipynb file. 
