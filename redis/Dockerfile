FROM redis
RUN mkdir -p /usr/local/etc/redis
COPY ./config/redis.conf /usr/local/etc/redis/redis.conf
CMD [ "redis-server",  "/usr/local/etc/redis/redis.conf" ]
