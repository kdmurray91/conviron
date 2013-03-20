conviron
========

Control software for the conviron growth chambers and heliospecta LED arrays

Installation:
============

To install this software, please run:
```python3 setup.py install```
(Preferably within a virualenv)

Running conviron:
=================

All configuration values are stored in two .ini configuration files. These are
conviron.ini and monitor.ini.

To run the control module, please run:
```python3 -m conviron <csv_path> [<ini_path>]```

By default, the conviron module uses "./conviron.ini" as its config file.
You now must supply the CSV file on the command line.

To run the monitor module, please run:
```python3 -m conviron.monitor [<ini_path>]```

By default, the conviron module uses "./monitor.ini" as its config file.
