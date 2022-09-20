# build image
docker build -t speedtest-cli .

# show arguments
docker run --rm speedtest-cli --help

# test download-speed
docker run --rm speedtest-cli --no-upload

