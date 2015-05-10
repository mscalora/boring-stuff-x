# kmlutil

### Dependencies:

* lxml
* pykml
* attrdict

### To install dependencies:

    pip install lxml pykml attrdict

## Example Usage:

### View contents of file:

    **$** kmlutil --tree --list-detail sample.kml
    Tracks                                   Folder   7456   19.62km    2.63m/pt
      Points                                 Folder      0    0.00km    0.00m/pt
        UNNAMED                              Point  [3728 occurances]
      Paths                                  Folder   3728   19.62km    5.26m/pt
        Current Track: 02 MAY 2015 07:18 001 Path     3728   19.62km    5.26m/pt

```bash
for i in *.kml ; then
   echo $i
fi
```
