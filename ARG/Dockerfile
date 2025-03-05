ARG version
FROM almalinux:${version:-9}
ARG course="DevOps with AWS" \
    duration="130 hrs"
ENV duration=$duration
RUN echo "course:$course, duration:$duration"
CMD ["sleep", "100"]