# Covid Wastewater Dashboards

This repository contains a list of national SARS-CoV-2 wastewater dashboards.

## Contributing

Are you aware of a national wastewater dashboard not mentioned in this list?
Please feel free to file a PR adding it. Non-national dashboards will only be
accepted if national dashboards for that country are not yet available.

## Dashboards

| Country Name  | Data Source                                                                        | Data Processor                                                                     | Dashboard           |
| ------------- | ---------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------- | ------------------- |
| Austria       | [Bundesministerium für Soziales, Gesundheit, Pflege und Konsumentenschutz][bsgpkg] | [Bundesministerium für Soziales, Gesundheit, Pflege und Konsumentenschutz][bsgpkg] | [link][austria]     |
| Canada        | Unknown                                                                            | [Covid 19 Resources Canada](https://covid19resources.ca/about-us/)                 | [link][canada]      |
| Canada        | Various Provincial Sources                                                         | [Government of Canada](govcan)                                                     | [link][canada2]     |
| Denmark       | [Statens Serum Institut][SSI]                                                      | [Statens Serum Institut][SSI]                                                      | [link][denmark]     |
| Finland       | [Finnish Institute for Health and Welfare][THL]                                    | [Elisa Oinonen](https://www.linkedin.com/in/elisaoi/)                              | [link][finland]     |
| Germany       | [Bundes Ministerium fur Gesundheit][bmg]                                           | [Bundes Ministerium fur Gesundheits][bmg]                                          | [link][germany]     |
| Ireland       | [Health Protection Surveillance Center][hpsc]                                      | [Health Protection Surveillance Center][hpsc]                                      | [link][ireland]     |
| Netherlands   | [Ministerie van Volksgezondheid, Welzijn en Sport][vws]                            | [Ministerie van Volksgezondheid, Welzijn en Sport][vws]                            | [link][netherlands] |
| New Zealand   | [Institute of Environmental Science and Research][esr]                             | [Institute of Environmental Science and Research][esr]                             | [link][nz]          |
| Scotland      | [Public Health Scotland][phs]                                                      | [Public Health Scotland][phs]                                                      | [link][scotland]    |
| Switzerland   | [Eawag][Eawag]                                                                     | [Eawag][Eawag]                                                                     | [link][switzerland] |
| United States | [Biobot Analytics](https://biobot.io/about/)                                       | [Biobot Analytics](https://biobot.io/about/)                                       | [link][usa1]        |
| United States | [Centers for Disease Control and Prevention][cdc]                                  | [Centers for Disease Control and Prevention][cdc]                                  | [link][usa2]        |

[austria]: https://abwassermonitoring.at/dashboard/
[canada2]: https://health-infobase.canada.ca/covid-19/wastewater/
[canada]: https://covid19resources.ca/covid-hazard-index
[denmark]: https://www.ssi.dk/sygdomme-beredskab-og-forskning/sygdomsovervaagning/c/covid-19---spildevandsovervaagning
[finland]: https://www.koronatilastot.fi/fi/jatevesi/
[germany]: https://corona-pandemieradar.de/de/abwasser
[ireland]: https://www.hpsc.ie/a-z/nationalwastewatersurveillanceprogramme/2024wastewatersurveillanceprogrammereports/
[netherlands]: https://coronadashboard.rijksoverheid.nl/landelijk/rioolwater
[nz]: https://poops.nz
[scotland]: https://scotland.shinyapps.io/phs-respiratory-covid-19/
[switzerland]: https://sensors-eawag.ch/sars/geneve.html
[usa1]: https://biobot.io/data/
[usa2]: https://www.cdc.gov/nwss/rv/COVID19-nationaltrend.html

[bsgpkg]: https://www.sozialministerium.at
[SSI]: https://www.ssi.dk
[THL]: https://thl.fi/en/main-page
[bmg]: https://www.bundesgesundheitsministerium.de
[vws]: https://www.rijksoverheid.nl/ministeries/ministerie-van-volksgezondheid-welzijn-en-sport
[hpsc]: https://www.hpsc.ie
[phs]: https://www.publichealthscotland.scot
[Eawag]: https://www.eawag.ch/en/
[govcan]: https://www.canada.ca
[esr]: http://www.esr.cri.nz/
[cdc]: https://www.cdc.gov

† This signifies a non-national wastewater dashboard. Because having some data
is better than no data.

## Why?

Wastewater monitoring is one of the most reliable ways to estimate the current
prevalence of diseases in a given region. Access to data enables people to make
informed decisions, researchers to analyze trends, and advocates to rally for
change.

I've suffered both death and disability in my family because of Covid. I have
friends whose lives have been ravaged by long-Covid. And in 2022 it took me out
for nearly six months too. Luckily I was able to almost fully recover -
something which does not happen for many.

Ignorance is not a solution, and change is only granted to those who demand it.
Covid is a disability issue. Covid is a worker's rights issue. Covid is an
economic issue. And Covid is also entirely preventable. We need change, and we
have the data to back that up. However that data is unevenly distributed, and so
this repository exists to more evently distribute it.

## What can I do?

Right now this is just a list of national dashboards. If you know of any other
dashboards, please contribute them to the list. If I had the time, I'd start
by writing (Rust) programs to begin archiving the data from the various dashboards
too and store them in-tree. Not to analyze directly - but to save others from
having to pull the data themselves, and eventually to even normalize so it can
be queried in a standard form. If someone wants to volunteer their time to do
this, I'll happily review any contributions which can get us closer to that.

