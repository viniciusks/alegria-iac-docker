FROM jenkins/jenkins:lts

# if we want to install via apt
USER root

RUN apt-get update && apt-get install -y python python3 python3-venv zip

USER jenkins
