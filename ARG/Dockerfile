ARG version
FROM almalinux: ${version:-9}
RUN dnf install nginx -y
WORKDIR /app
ARG course="docker"
ARG trainer="sivakumar"
ARG duration="10hrs"
RUN echo "course: ${course} trainer: ${trainer} duration: ${duration}"