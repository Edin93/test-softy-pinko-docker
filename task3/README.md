#### First terminal building/running the backend:

* `docker build -f ./back-end/Dockerfile -t softy-pinko-back-end:task3 ./back-end`

* `docker run -p 5252:5252 -it --rm --name softy-pinko-back-end-task3 softy-pinko-back-end:task3`

#### Second terminal building/running the front-end:

* `docker build -f ./front-end/Dockerfile -t softy-pinko-front-end:task3 ./front-end`

* `docker run -p 9000:9000 -it --rm --name softy-pinko-front-end-task3 softy-pinko-front-end:task3`

