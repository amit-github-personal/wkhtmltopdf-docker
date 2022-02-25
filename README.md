# WkhtmlToPDF Docker Image

This is a docker image of wkhtmltopdf tool.

# Run Instructions 
- Build the docker file by using the command ` docker build -t wkhtml:0.1 .`
- Run the compose file with command `docker-compose -f /pathtocomposefile up -d`
- Now you can go inside the container shell `docker container exec -it wkhtmltopdf-wkhtml-1 bash`
- Execute the commands `wkhtmltopdf https://www.google.com /output/google.pdf`
- The output files will be there in output folder in your host system
