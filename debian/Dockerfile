FROM codelios/hugo:0.68.0-debian

LABEL description="Docker image for CI continuous integration using hugo static site generator - Debian based"
LABEL vendor="CodeLios"

WORKDIR /

ENV BUILD_USER=codelios
RUN addgroup "$BUILD_USER" && \
adduser --disabled-password --gecos "" --ingroup "$BUILD_USER" "$BUILD_USER"
