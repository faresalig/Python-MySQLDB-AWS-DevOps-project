FROM mysql:latest

# استخدم MySQL client فقط بدل السيرفر
COPY init-db.sh /init-db.sh
RUN chmod +x /init-db.sh

ENTRYPOINT ["/init-db.sh"]
