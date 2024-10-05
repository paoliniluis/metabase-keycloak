FROM quay.io/keycloak/keycloak:20.0 as builder
WORKDIR /opt/keycloak/providers

RUN curl -L -o scim.jar https://github.com/Captain-P-Goldfish/scim-for-keycloak/releases/download/kc-20-b1/scim-for-keycloak-kc-20-b1.jar && \
    chmod 640 scim.jar && \
    chown keycloak:keycloak scim.jar && \
    /opt/keycloak/bin/kc.sh build

ENTRYPOINT ["/opt/keycloak/bin/kc.sh"]