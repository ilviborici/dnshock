# Dnshock

A script that generates random HTTP/DNS traffic noise in the background while you go about your regular web browsing, to make your web traffic data less valuable for selling and for extra obscurity.


# Run the script

```
python dnshock.py --config config.json
```

The program accepts a number of command line arguments:
```
$ python dnshock.py --help
usage: dnshock.py [-h] [--log -l] --config -c [--timeout -t]

optional arguments:
  -h, --help    show this help message and exit
  --log -l      logging level
  --config -c   config file
  --timeout -t  for how long the crawler should be running, in seconds
```
config file argument is required unlike the other parameters.
