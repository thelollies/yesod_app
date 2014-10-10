# Dockerfile
FROM busybox
# Add VOLUMEs to allow backup of config, logs and databases
# Not using volume for config or dbs: "/etc/postgresql", "/var/log/postgresql", 
RUN adduser -D postgres
USER postgres
VOLUME  ["/var/lib/postgresql/9.3/main"]


CMD /bin/sh
