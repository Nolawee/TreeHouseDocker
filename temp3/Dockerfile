FROM ubuntu
RUN useradd treehouse
WORKDIR /app
RUN chown treehouse /app
USER treehouse
RUN whoami > whoami.txt
CMD whoami
