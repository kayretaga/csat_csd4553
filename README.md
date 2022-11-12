
* BUILD
- docker build -t kayretaga/nodejs-image-demo-csat-1 .
- docker run -d -p 4000:3000 kayretaga/nodejs-image-demo-csat-1

* OR
docker run --name nodejs-image-demo-csat-1 -p 4000:3000 -d kayretaga/nodejs-image-demo-csat-1

* PUSH
docker desktop login
docker push kayretaga/nodejs-image-demo-csat-1

* REFERENCES