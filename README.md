# ai-adoption-data
- a DiD analysis for AI adoption data within the EU, crossed with inequality metrics.
- I would recommend opening the ipynb in [google colab](https://colab.research.google.com/) for simplicity
- remember to upload the csv files too

# Dataset sources

WID (used for years 2012-2023 of inequality data)
- [URL](https://wid.world/)

EU data (used for years 2023-2024 of AI adoption)
- [URL](https://ec.europa.eu/eurostat/statistics-explained/index.php?title=Use_of_artificial_intelligence_in_enterprises)

OECD data (used for years 2021-2022 of AI adoption)
- OECD 2025
- ICT Access and Usage by Businesses
- Measure: Businesses using artificial intelligence (AI) 
- Employment size class: 10 or more
- Combined unit of measure: Percentage of enterprises
- [URL](https://data-explorer.oecd.org/vis?tm=AI&pg=0&snb=12&df[ds]=dsDisseminateFinalDMZ&df[id]=DSD_ICT_B%40DF_BUSINESSES&df[ag]=OECD.STI.DEP&df[vs]=1.0&dq=AUS%2BAUT%2BBEL%2BCAN%2BCOL%2BCZE%2BDNK%2BEST%2BFIN%2BFRA%2BDEU%2BGRC%2BISL%2BHUN%2BIRL%2BISR%2BITA%2BJPN%2BKOR%2BLVA%2BLTU%2BLUX%2BMEX%2BNLD%2BNZL%2BNOR%2BPOL%2BPRT%2BSVK%2BSVN%2BESP%2BSWE%2BCHE%2BTUR%2BGBR%2BUSA%2BBRA%2BBGR%2BHRV%2BROU.A.G14_B.PT_ENT._T.S_GE10%2BS_GE100&pd=2005%2C2024&to[TIME_PERIOD]=false&vw=tb) (accessed on 25/04/2025)

# The DiD segment of this code has been adapted from the following repo (many thanks)
- https://github.com/xbeat/Machine-Learning/blob/main/Difference-in-Differences%20(DiD)%20Analysis%20in%20Python.md
