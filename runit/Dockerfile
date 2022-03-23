FROM busybox

RUN mkdir -p /etc/sv/test
COPY run_test /etc/sv/test/run
RUN chmod +x /etc/sv/test/run

CMD ["runsv", "/etc/sv/test"]