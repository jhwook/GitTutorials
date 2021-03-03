# GitTutorials
### Installation
<pre>
cd / home
git clone https://github.com/jhwook/Docker-Practice
cd Docker-Practice
</pre>
### Run
<pre>
# Login For Private Docker Repository
docker login
docker pull jhwook/docker-practice
docker run -p 80:80 -v /home/Docker-Practice/Project:/var/www/html
</pre>
