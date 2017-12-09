FROM registry.gitcity.sk/cakehub/cakeapp:fpm

COPY docker-entry.sh /usr/local/bin/docker-entry
RUN chmod +x /usr/local/bin/docker-entry

CMD ["docker-entry"]
