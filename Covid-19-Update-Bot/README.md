# Covid-19-Update-Bot
Covid-19 Update Bot that will Notifiy about the current covid-19 Cases, Deaths, Recovered

[![forthebadge made-with-python](http://ForTheBadge.com/images/badges/made-with-python.svg)](https://www.python.org/)                  [![Python 3.6](https://img.shields.io/badge/python-3.6-blue.svg)](https://www.python.org/downloads/release/python-360/)          [![PyPI license](https://img.shields.io/pypi/l/ansicolortags.svg)](https://pypi.python.org/pypi/ansicolortags/)





# Dependencies:
*json*

```
pip install json
```
*win 10 toast*

```
pip install win10toast
```

*Initially it shows the cases worldwide it will notify after every hour*

*If you want to see cases for india or any other country then change this line in the code*
```
r = requests.get('https://coronavirus-19-api.herokuapp.com/countries/india')
```





