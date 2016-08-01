FROM hypriot/rpi-alpine-scratch

ADD carbon-relay-ng /bin/

VOLUME /conf

ENTRYPOINT ["/bin/carbon-relay-ng"]

CMD ["/conf/carbon-relay-ng.ini"]
