### JBoss EJB client using a scoped context

1. unzip EAP distributions
2. add user EAP with this command:  `bin/add-user.sh -a -g users -u joe -p joeIsAwesome2013!`
3. build `server` project, deploy it
4. run `client` project using `mvn exec:exec`

