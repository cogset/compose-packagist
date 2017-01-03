# Redis
FROM redis:3.2

# Log directory.
RUN mkdir /logs && chown redis:redis /logs

# Run with config file.
CMD ["redis-server", "/etc/redis.conf"]
