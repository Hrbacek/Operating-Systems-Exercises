FROM ubuntu:16.04
ENV EXERCISE_ROOT="/"
WORKDIR ${EXERCISE_ROOT}
RUN apt update && apt install -y man-db
ENTRYPOINT [ "/bin/bash" ]