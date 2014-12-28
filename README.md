auth_siucacm
===========

Authentication system for SIUC ACM machines.

OpenLDAP is kind of not a super great solution since configuring/management is a pain. Also enforcing membership may be difficult. We are going to try a *SQL-backed authentication solution that will also bundle in support for 2nd-factor verification, whether it be Google authenticator or hardware token.

We hope to include:
 * Web interface for user management
 * Command-line interface for user management
 * 2nd factor verification (Google auth or hardware token)
 * Support for application-specific passwords for things that require them (e.g. mail)
