# Running the server with in-memory DB
docker build --rm -t josedominguez/liferay-master-9090 .
docker run -p 9090:9090 -p11311:11311 josedominguez/liferay-master-9090



