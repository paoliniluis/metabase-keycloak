Contents of this docker-compose
===============================

This stack should be used to test SAML SSO

- An enterprise container (configured with postgres database) exposed on port 3000
- A KeyCloak server exposed on port 9090 (with SCIM support)
- A postgres database that is used as the application database for Metabase (exposed on port 5432)

Everything is glued up on the metanet1 network
