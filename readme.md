# Whatsthatevent

Small convince tool to lookup windows ids and return triggers them.

Event logs from the following versions are available

- Win2008
- Win2012R2
- Win2016
- Win10+
- Win2019
- Win2000
- XP
- Win2003


## Usage


```
usage: whatistheevent [-h] [--legacy] event_id

positional arguments:
event_id    event id to query from Win2008, Win2012R2, Win2016 and Win10+, and Win2019

options:
-h, --help  show this help message and exit
--legacy    event id to query from Win2000, XP, and Win2003
```

## Examples 


```
$ whatsthatevent 1100

Event ID: 1100: The event logging service has shut down
```

```
$ whatsthatevent --legacy 512

Legacy event ID: 512: Windows NT is starting up
```
