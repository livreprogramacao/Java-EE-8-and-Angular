Chapter 4
---

```
java -jar payara-micro-5.182.jar --deploy ims-micro-users/target/ims-micro-users.war --port 8081
java -jar payara-micro-5.182.jar --deploy ims-micro-tasks/target/ims-micro-tasks.war --port 8082
java -jar payara-micro-5.182.jar --deploy ims-micro-notify/target/ims-micro-notify.war --port 8083


java -jar /home/user/Downloads/Java-EE-8-and-Angular/payara-micro-5.182.jar --deploy target/ims-micro-tasks.war --outputUberJar target/ims-micro-tasks.jar

docker build -t jee8ng/ims-micro-tasks .
```

Chapter 7
---

```
cd Chapter14/ims-security
mvn package install

cd /home/user/Downloads/Java-EE-8-and-Angular/Chapter07/putting-together-ims/ims-users
sh buildAndRun.sh

cd /home/user/Downloads/Java-EE-8-and-Angular/Chapter07/putting-together-ims/ims-comments
sh buildAndRun.sh

cd /home/user/Downloads/Java-EE-8-and-Angular/Chapter07/putting-together-ims/ims-issues
sh buildAndRun.sh

cd /home/user/Downloads/Java-EE-8-and-Angular/Chapter07/putting-together-ims/ims-chat
sh buildAndRun.sh

we should now have Docker containers started locally with port bindings, shown as the following:

```
docker ps --format "{{.Image}}\t{{.Names}}\t{{.Ports}}"
```


sudo /etc/init.d/apache2 stop