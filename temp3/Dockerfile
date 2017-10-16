FROM ubuntu
RUN useradd treehouse
WORKDIR /app
# change owner to treehouse 
RUN chown treehouse /app
USER treehouse
RUN whoami > whoami.txt
CMD whoami
