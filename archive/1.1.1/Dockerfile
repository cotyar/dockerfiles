FROM mono:4.4.2.11
LABEL Description="Akka.NET Mono Continuous Integration Base Image" Vendor="Akka.NET" Version="1.1.1"

RUN echo "deb http://download.mono-project.com/repo/debian wheezy/snapshots/4.4.2.11 main" \
    && apt-get update \
    && apt-get install -y git \
    && rm -rf /var/lib/apt/lists/*