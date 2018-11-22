FROM postgres:10
RUN apt-get update \
 && apt-get install -y eatmydata \
 && apt-get autoremove -y \
 && rm -rf /var/lib/apt/lists/*

ENTRYPOINT [ "/usr/bin/eatmydata", "/usr/local/bin/docker-entrypoint.sh" ]
CMD ["postgres"]
