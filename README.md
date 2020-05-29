HackMD
===

```
You did not specify either --add or --del or --reset!

Command-line utility to create users for email-signin.

Usage: bin/manage_users [--pass password] (--add | --del) user-email
        Options:
                --add   Add user with the specified user-email
                --del   Delete user with specified user-email
                --reset Reset user password with specified user-email
                --pass  Use password from cmdline rather than prompting
```

## Add user

```bash
docker-compose run --rm app bin/manage_users --add foo@bar.com
```

