# Running the server with in-memory DB
docker build --rm -t josedominguez/liferay-master-9091 .
docker run -p 9091:9091 -p11312:11312 josedominguez/liferay-master-9091
