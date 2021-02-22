FROM camunda/camunda-bpm-platform:latest
RUN apt-get update
RUN apt-get install -y curl
EXPOSE 8080 
CMD ["--silent", "http://localhost:8080/camunda/app/welcome"]
ENTRYPOINT ["curl"]
