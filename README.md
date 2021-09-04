# plot-covid-graphs
Plot covid-related graphs using Python.

This is my adaptation of the [babsyco/COVID19_cases_deaths_vaccinations](https://github.com/babsyco/COVID19_cases_deaths_vaccinations) repository.

It uses the the [Our World In Data](https://ourworldindata.org/explorers/coronavirus-data-explorer?zoomToSelection=true&minPopulationFilter=1000000&time=59..latest&pickerSort=asc&pickerMetric=location&hideControls=true&Metric=People+fully+vaccinated&Interval=Cumulative&Relative+to+Population=true&Align+outbreaks=false&country=~ISR) COVID-19 dataset available [here](https://github.com/owid/covid-19-data/blob/master/public/data/owid-covid-data.csv).

# Instructions
1. Open the Google Colab notebook by going to [this](https://colab.research.google.com/github/badan-cloud/plot-covid-graphs/blob/main/plot-covid-graphs.ipynb) url.
2. You'll get a message about this notebook not being authored by Google. Run it anyway.
3. You'll see a lot of code boxes (cells). A ▶ (Play) button appears when you hover your mouse over a cell. Click this button to run the cell (alternatively, you could run Ctrl + Enter to run the current cell). Run the cells **in order from top to bottom**.
4. When running the "SAVE PLOTS" cell, you'll be prompted to answer whether you want to download the plots or not. Answer `y` for "yes" and `n` for "no".
5. The last cell contains examples for plotting different graphs. Also it contains examples on how to change the population, how to get the list of countries, fields. etc. Uncomment any example by removing the `#` symbol in the beginning of the line (and all trailing spaces), or by pressing `Ctrl + #` while the cursor is on the needed line. Craft the function parameters according to the instructions and run the cell.
6. You can add additional cells and run your own code there.
