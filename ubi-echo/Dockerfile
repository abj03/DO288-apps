#FROM registry.access.redhat.com/ubi8/ubi:8.0
FROM registry.access.redhat.com/ubi9/ubi-micro
RUN mkdir /apps
RUN echo "while true; do echo test; sleep 5; done" > /apps/out.sh

USER 1001
#CMD bash -c "while true; do echo test; sleep 5; done"
ENTRYPOINT [ "bash", "-c", "while true; do echo test; sleep 5; done"]
