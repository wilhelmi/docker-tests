FROM nwilhelmi/redis_base
MAINTAINER James Turnbull <james@example.com>
ENV REFRESHED_AT 2016-06-01
ENTRYPOINT [ "redis-server", "--logfile /var/log/redis/redis-replica.log", "--slaveof redis-primary 6379" ]