# extractor-series

Extractor-Series is a set of scripts written in Bash to extract download links from TV series of pirated pages.

Just for the record, I did not create this tool to tolerate piracy, but it is inevitable and I know someone will use it for such purposes.
Regardless, the way you use this tool is entirely your responsibility.
Respect and support the creators of the series, along with their cast.

### Requirements:
* cURL - `sudo apt install curl` or `sudo yum install curl`
* pup (Only in SeriesGato and Fanpelis) - (x64 version bundled, you can get other versions from [here](https://github.com/ericchiang/pup/releases))


### Usage:
```
./extractor-<page>.sh <id of serie> <episodes of 1 season> [<episodes of 2 season>...<episodes of 15 season>]
```

### Examples:
```
./extractor-seriesgato.tv.sh 18-5-the-good-doctor-328634.html 18 3
./extractor-fanpelis.com.sh el-joven-sheldon 22
```

### Supported pages:
| Title | URL | Servers | Note |
|---|---|---|---|
| SeriesGato | https://www.seriesgato.tv | Openload, Streamango | It doesn't work with series that contain numbers on their name |
| Fanpelis | http://fanpelis.com | Openload, Rapidvideo ||
