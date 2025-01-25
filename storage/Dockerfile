FROM drakkan/sftpgo:v2.6.4
LABEL org.opencontainers.image.description="Custom version of sftpgo base image with curl installed for because its used by custom scripts"
USER 0:0
RUN apt-get update && apt-get install -y curl
USER 1000:1000
