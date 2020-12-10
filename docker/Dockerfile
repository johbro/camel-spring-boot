FROM fabric8/s2i-java:2.3

MAINTAINER "John Browning" "johnb@redhat.com"

COPY --chown=default:0 ./../rest-user/target/camel-example-rest-user-0.0.1-SNAPSHOT.jar /opt/jboss/
RUN chmod a+r+w /opt/jboss/camel-example-rest-user-0.0.1-SNAPSHOT.jar


CMD ["java -jar camel-example-rest-user-0.0.1-SNAPSHOT.jar"]
