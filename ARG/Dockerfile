ARG version
FROM almalinux:${version:-8}
#RUN cat /etc/*release
ARG COURSE=Docker
ARG LEARNER=Kalyan
ARG Duration=120HRS
ENV Duration=${Duration}
RUN echo "Course is: ${COURSE}, Learner is: ${LEARNER}, Duration is: ${Duration}"
CMD [ "sleep","100" ]