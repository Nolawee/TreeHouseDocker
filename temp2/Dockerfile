FROM ubuntu
#Set environment variables
ENV appDir=/app message="Welcome to our app!"
WORKDIR $appDir
RUN echo $message > README.txt
CMD echo READ ${appDir}/README.txt for a friendly greeting!
