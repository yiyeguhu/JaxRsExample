# Example on JAX-RS Web Application with Glassfish

Related blog article: [Ant-Ivy to Manage Dependencies Like in Maven](http://yiyeguhu.org/2015/11/06/ant-ivy-to-manage-dependencies-like-in-maven/)

## Packaging
```
mvn clean package
```

## Deploying to Glassfish
```
mvn embedded-glassfish:run
```

Go to [http://localhost:8080/jaxrsexample/hello/world](http://localhost:8080/jaxrsexample/hello/world)
