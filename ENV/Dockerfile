# dockerfiles/ENV/Dockerfile
FROM almalinux:9
RUN dnf install nginx -y
EXPOSE 80
ENV course="docker" \
    trainer="sivakumar" \
    duration="10hrs"
CMD ["sleep", "500"]