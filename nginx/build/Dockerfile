FROM nginx:1.15.3

RUN apt-get update && \
    apt-get dist-upgrade -y && \
    apt-get install -y nginx-extras ca-certificates gettext-base && \
    rm -rf /var/cache/apt && rm -rf /var/lib/apt