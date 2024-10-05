Contents of this docker-compose
===============================

This stack should be used to test SAML SSO

- An enterprise container (configured with postgres database) exposed on port 3001
- A KeyCloak server exposed on port 8080
- A postgres database that is used as the application database for Metabase (exposed on port 5432)

Everything is glued up on the metanet1 network