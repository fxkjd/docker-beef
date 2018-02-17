# Dockerfile for Beef

## Build

Add the config.yaml file in the folder. Then:

>$ docker build -t fxkjd/beef .

## Usage

>$ docker run -it -p 3000:3000 -v /[HOST-DIR]/config.yaml:/opt/beef/config.yaml fxkjd/beef

Beef will be available at http://localhost:3000/ui/panel
