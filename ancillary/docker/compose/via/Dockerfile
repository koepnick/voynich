FROM nginx:1.25-alpine-slim

RUN mkdir /app /data
WORKDIR /app
RUN apk add wget unzip
#RUN wget 'https://www.robots.ox.ac.uk/~vgg/software/via/downloads/via3/via-3.0.12.zip'
RUN wget 'https://www.robots.ox.ac.uk/~vgg/software/via/downloads/via-2.0.12.zip'
RUN unzip via-2.0.12.zip
EXPOSE 8000
COPY data/nginx/conf.d/via.conf /etc/nginx/conf.d/

#CMD ["python", "-m", "http.server", "-d", "/app/via-2.0.12/"]
