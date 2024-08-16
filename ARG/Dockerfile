FROM almalinux:8
ARG username
RUN adduser $username
USER $username
ARG NAME
ARG ROLE
RUN echo "NAME: ${NAME}, ROLE: ${ROLE}"
ENV NAME=${NAME}
ENV ROLE=${ROLE}
CMD ["sleep", "100"]