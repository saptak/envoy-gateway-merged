FROM alpine
LABEL org.opencontainers.image.title="Envoy Gateway" \
    org.opencontainers.image.description="Manage Envoy Gateway directly from Docker Desktop" \
    org.opencontainers.image.vendor="Saptak Sen" \
    com.docker.desktop.extension.api.version="0.3.4" \
    com.docker.extension.screenshots="" \
    com.docker.extension.detailed-description="" \
    com.docker.extension.publisher-url="" \
    com.docker.extension.additional-urls="" \
    com.docker.extension.changelog=""

COPY docker-compose.yaml .
COPY metadata.json .
COPY ui ui
