Contents of this docker-compose
===============================

This stack should be used to test SAML SSO

- An enterprise container (configured with postgres database) exposed on port 3000 (needs to be set up)
- A KeyCloak server exposed on port 8080 (admin/password)
- A mail server on port 3001 to check for emails that Metabase server sends

Everything is glued up on the metanet1 network

Note: to configure Keycloak with Mebase, please follow this guide: https://www.metabase.com/docs/latest/people-and-groups/saml-keycloak