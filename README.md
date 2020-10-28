# German Cities Population Scraper

This project scrapes [this website](https://www.citypopulation.de/en/germany/cities/) for german cities and their respective estimated
population. 
Only the estimated population of *2019-12-31* is scraped from the website.

## Set-up (optional)

Run the following commands to install all the dependencies into a virtual
environment

### Linux/Mac Bash:

```
python3 -m venv venv

source venv/bin/activate
pip install -r requirements.txt
```

### Windows Cmd:

```
py -m venv venv

.\venv\Scripts\activate
pip install -r requirements.txt
```

After running all cells of the notebook, you'll find the saved scraped data in
the *cities_and_population.csv*, with columns; *city*, *status*, *adm*
(abbreviated administrative state), and
*population*.

