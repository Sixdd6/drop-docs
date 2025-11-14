# Simple
Simple authentication (or simple auth) is a basic username and password combination. It's the default for Drop, and is the fallback authentication mechanism if Drop is unable to initialise any others.
Simple authentication works on a system of invites.

## Creating an invite
For a detailed guide to creating invites see [User Accounts](../guides/user_accounts.md)

## Disabling simple auth
If you've configured another authentication mechanism, you can disable simple by setting the environment variable `DISABLE_SIMPLE_AUTH` to "true".
