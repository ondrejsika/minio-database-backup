FROM mysql:8
COPY --from=minio/mc /usr/bin/mc /usr/local/bin/mcli
COPY minio_database_backup /usr/local/bin/
VOLUME /data