FROM osixia/openldap

LABEL maintainer="amanshu@gmail.com"

ARG LDAP_PASSWORD=""
ENV LDAP_ORGANISATION="Example" \
    LDAP_DOMAIN="example.org" \
    LDAP_ADMIN_PASSWORD=${LDAP_PASSWORD}

COPY bootstrap.ldif /container/service/slapd/assets/config/bootstrap/ldif/50-bootstrap.ldif
