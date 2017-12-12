# Smart-Mirror
Raspberry powered mirror which can display the news, weather, and time.

## Installation and Updating

### Install your dependencies
make sure you have [pip](https://pip.pypa.io/en/stable/installing/) installed before doing this

```
sudo pip install -r requirements.txt
```

```
sudo apt-get install python-imaging-tk
```

### Add your api token
Use `nano` to edit you file

```
nano smartmirror.py
```

replace `weather_api_token` with the token you got from forecast.io

## Running
To run the application run the following command in this folder

```
python smartmirror.py
```
