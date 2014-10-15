vnsmtpd
=======

Very nice smtp server.

Key features:
* is a small, multithreaded MTA server written in C;
* it adheres to the RFC standards;
* all currently used SMTP verbs are implemented;
* dead verbs are left out;
* is delivering messages in Maildir format;
* the configuration is simple and understandable;
* it uses domains, users and aliases derived from Postfix;
* it has seemless integration with Courier-IMAP configuration;
* all configuration details reside in a MySQL database;
* it has all logging written to a MySQL database;
* it has builtin spam heuristics;
* optional it will use external spam databases.

Current status:
* is now in alpha test replacing my own Postfix server;
* when proven quality and reliability are reached, it will be published in beta.



