FROM jenkinsci/blueocean:latest

ENV CASC_JENKINS_CONFIG /var/jenkins_home/casc_configs

COPY ./jenkins_config /var/jenkins_home/casc_configs

RUN install-plugins.sh \
  configuration-as-code \
  configuration-as-code-support


