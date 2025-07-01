FROM --platform=linux/amd64 rhel9-ruby-node as stage-amd64

FROM --platform=linux/arm64/v8 rhel9-ruby-node as stage-arm64

ARG TARGETARCH

FROM stage-${TARGETARCH} as final

COPY . /build
RUN /build/install.sh && rm -rf /build
