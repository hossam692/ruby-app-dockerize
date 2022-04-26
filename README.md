# ruby-app-dockerize

This project is to transform the dockerized rails app in the link
https://semaphoreci.com/community/tutorials/dockerizing-a-ruby-on-rails-application
into a K8S cluster using minikube

- Dockerfiles are transformed to YAML deployment files.
- Environmental Variables are passed to the pods through ConfigMaps files or Secrets files according to their senstivity.
- Services are attached to each Pod deployment file.
