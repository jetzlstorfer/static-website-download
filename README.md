# Static Website Downloader

This project allows to take a snapshot of a website and store its contents including js, css, images, etc locally.

The script will download the contents of the website to the current folder. The folder can be changed, by setting the `-P` variable to another destination, e.g., `/my/path`

## Usage

```
wget -P . -mpck --user-agent="" -e robots=off --wait 1 -E --restrict-file-names=ascii,windows https://www.your-website-url.com/

```

### Explanation of the script

The details of the command can be investigated by [explainshell.com](https://www.explainshell.com/explain?cmd=wget+-P+.+-mpck+--user-agent%3D%22%22+-e+robots%3Doff+--wait+1+-E+--restrict-file-names%3Dascii%2Cwindows+https%3A%2F%2Fwww.your-website-url.com%2F).

