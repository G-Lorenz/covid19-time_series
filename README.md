# COVID19 Time series

These time series are fetched from JHU's [daily reports](https://github.com/CSSEGISandData/COVID-19/tree/master/csse_covid_19_data/csse_covid_19_daily_reports) using my [program](linktorepo)

##Datasets
This repo hosts the time series of the states that have at least one 'Admin1' with available data.
The datas are organized in two different ways:

### rows
Data series are [JHU's like](https://github.com/CSSEGISandData/COVID-19/tree/master/csse_covid_19_data/csse_covid_19_time_series).

Admin2 Province Country date1 date2 etc.

### cols
Data series are organized in columns, so they are easily plotted with tools like Gnuplot, or parsed with languages like C or Python.

Admin2
Province
Country
date1
date2
etc.

## Bugs
This bugs are due to my [program](linktorepo).
When JHU adds a 'province', the old datas are lost.
Countries with a space or a special character inside the name are not included. At this moment, only UK is in this situation.

## License
If you publish these time series, or you use them in a website/article (etc.) please provide a link to this repo.

## Links
* [JHU's official time series](https://github.com/CSSEGISandData/COVID-19/tree/master/csse_covid_19_data/csse_covid_19_time_series) : only few countries are shown completely, but they are useful to parse World data at country level and US data at Admin2 level.

* [Italian 'Protezione Civile' official data](https://github.com/pcm-dpc/COVID-19) : several kinds of data collected at Admin2 level.
