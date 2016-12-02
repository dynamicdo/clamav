ClamAV
======

ClamAV is a simple PHP library to interface with the clamd anti-virus daemon. It was written as all of the libraries out
there for interfacing with ClamAV from PHP use ```exec('clamscan')```, which isn't exactly an ideal solution, as
```clamscan``` loads the entire database into memory each time it is run - this doesn't, so it scans a lot (lot!) faster.

## Installation

It is recommended to install Quahog through [composer](http://getcomposer.org).

```JSON
{
    "require": {
        "dyanmicdo/clamav": "0.*"
    }
}
```

#Credit

This is a fork of `jonjomckay/quahog` which is not really maintined.
