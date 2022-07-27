ARG ATLANTIS_VERSION=v0.19.6
FROM ghcr.io/runatlantis/atlantis:${ATLANTIS_VERSION}

ARG TERRAGRUNT_VERSION=v0.38.6
ADD --chmod=+x https://github.com/gruntwork-io/terragrunt/releases/download/${TERRAGRUNT_VERSION}/terragrunt_linux_amd64 /usr/local/bin/terragrunt
RUN chmod +x /usr/local/bin/terragrunt
