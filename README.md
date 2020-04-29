# Jenkins Pipeline to upload static website files to AWS S3

This project contains a Jenkinsfile which is used to configure a CI/CD pipeline. The first stage is to lint the html files in my Github repo when a change is detected. Second stage, if  linting is successful, uploads the files to a public S3 bucket which is used to host the static website.