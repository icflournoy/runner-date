# runner-date
Run a command for every date in a given range.

## Usage
The simplest example prints out each day over a range.

```bash
./runner-date 2017-07-15 2017-07-30 echo %date%
```

To change the resulting date format use

```bash
./runner-date -f '%d/%02d/%02d' 2017-07-15 2017-07-30 echo %date%
```
