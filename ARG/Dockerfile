FROM almalinux:9
ENV course="Devops with AWS" \
    trainer="Ajay kuma"
# here user1 is key someuser is default value
# ARG user1=someuser
ARG ${username:-some_user}
RUN echo "Hello ${trainer}" > /tmp/devops.txt
CMD ["sleep", "100"]