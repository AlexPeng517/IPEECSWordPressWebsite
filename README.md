# IPEECSWordPressWebsite
Usage: \
Step 1 \
`cd` to your cloned project folder \
\
Step 2 \
run `docker-compose up -d` \
\
Step 3 \
open browser and go to `localhost:8888` then follow the installation steps in WordPress \
\
To stop and remove running containers, use `docker-compose down` command \
\
Note that, even if you removed all running containers via `docker-compose down` command, the data and configurations including in MySQL, WordPress, and Nginx will still remain in the specific folder in the project, you can always re-use the data that would not be affected by any versions of images used to build the services.
