# MySQL
FROM mysql:5.7

# Directories.
RUN mkdir -p /mysql/{conf,data,logs} \
    && chown -R mysql:mysql /mysql

# Run with config file.
CMD ["mysqld", "--defaults-file=/mysql/conf/my.cnf"]

