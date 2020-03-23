# Notes


## Formatted equivalent of `date -Im`:

```
date  +'%Y-%m-%dT%H:%M%:z'
```

## Extract page range with qpdf:

```
$ qpdf infile.pdf --pages infile.pdf 1-10 -- output.pdf
```

## Systemd Cache Flushing

```
sudo systemd-resolve --flush-caches
```

Check stats:

```
sudo systemd-resolve --statistics
```

