# Investment analysis: where the money should go

Funding trend analysis for an asset management firm, built for the machine
learning and AI post graduate diploma at IIIT Bangalore.

## The problem

The firm invests inside a fixed band per round and wants English speaking
countries. That turns a broad question, where are the global trends, into a
narrow one: which sector, which funding stage and which country fit those
constraints at once.

## What is here

- `investment.ipynb` is the analysis, from merging the funding, company and
  sector data through to the recommendation
- `investment_analysis.zip` holds the supporting files

## Approach

Join funding rounds to companies and to a sector mapping, filter to the stages
and amounts that match the firm's constraints, then rank sector and country
pairs by total investment rather than by count, so a few large rounds do not
hide behind many small ones.

## Running it

```
pip install pandas numpy matplotlib jupyter
jupyter notebook investment.ipynb
```
