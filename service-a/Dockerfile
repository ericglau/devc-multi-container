FROM openliberty/open-liberty:kernel-java8-openj9-ubi

# Add config
COPY --chown=1001:0  target/liberty/wlp/usr/servers/demo/server.xml /config/
COPY --chown=1001:0  target/liberty/wlp/usr/servers/demo/bootstrap.properties /config/

# Add application
COPY --chown=1001:0  target/liberty/wlp/usr/servers/demo/apps/demo.war /config/apps/
