# Static Website Downloader

This project allows to take a snapshot of a website and store its contents including js, css, images, etc locally.

## Usage

```
wget -P . -mpck --user-agent="" -e robots=off --wait 1 -E --restrict-file-names=ascii,windows https://www.your-website-url.com/

```

