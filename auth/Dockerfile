FROM osixia/openldap

LABEL maintainer="cameron@shiell.co.uk"

ENV LDAP_ORGANISATION="Example" \
    LDAP_DOMAIN="example.org" \
    LDAP_ADMIN_PASSWORD="lightMongoose56"

COPY bootstrap.ldif /container/service/slapd/assets/config/bootstrap/ldif/50-bootstrap.ldif
