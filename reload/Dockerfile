FROM busybox:1.33.1

COPY ./build/linux/reload  /bin/reload
ENTRYPOINT [ "/bin/reload" ]
CMD        [ "--watch-path=/etc/prometheus/rules", \
             "--prometheus-url=http://127.0.0.1:9090" ]
