ARG version
FROM almalinux:${version:-9}
ENV course="Devops with AWS" \
    trainer="Ajay kumar"
# here user1 is key someuser is default value
# ARG user1=someuser
ARG  USERNAME=AjayKumar
RUN echo "Hello User: ${USERNAME}, image version: ${version}" > /tmp/devops.txt
CMD ["sleep", "100"]