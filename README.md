# lighthouse-docker

## Usage

```
docker pull inttt/lighthouse
$docker run -it -v $PWD/report/:/home/chrome/report --cap-add=SYS_ADMIN inttt/lighthouse --chrome-flags="--headless --disable-gpu" https://google.com
```
