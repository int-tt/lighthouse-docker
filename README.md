#lighthouse-docker

## Usage

```
$docker run -itv $PWD/report/:/home/chrome --cap-add=SYS_ADMIN lighthouse2 --chrome-flags="--headless --disable-gpu" https://google.com
```
