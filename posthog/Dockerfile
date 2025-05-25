FROM ghcr.io/posthog/posthog:86d6812c7de75c6c869b935e17baf45bf295bfd5

RUN apt-get update && apt-get install -y redis-server

CMD user/bin/redis-server & ./bin/docker
