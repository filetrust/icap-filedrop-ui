# icap-filedrop-ui
The file drop product UI delivered as part of the ICAP Program

## Develop CI Status
![CI](https://github.com/filetrust/icap-filedrop-ui/workflows/CI/badge.svg?branch=develop)

## Main CI Status
![CI](https://github.com/filetrust/icap-filedrop-ui/workflows/CI/badge.svg?branch=main)

To build the docker image
```
cd app

docker build -t icap-filedrop-ui .
```

To run the docker image
```
docker run -p 80:80 --rm icap-filedrop-ui
```
