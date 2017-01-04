# Redis
FROM redis:3.2

# Directories.
RUN mkdir -p /redis/{conf,data,logs}
    && chown -R redis:redis /redis

# Run with config file.
CMD ["redis-server", "/redis/conf/redis.conf"]
