log4j-smtp-example
==================

Example project that demonstrates how to use the [SMTPAppender](https://logging.apache.org/log4j/2.x/manual/appenders.html#SMTPAppender) of [Apache Log4j 2](http://logging.apache.org/log4j/2.x/) with [Mailtrap](https://mailtrap.io/).

## Usage

1. Sign up for [Mailtrap](https://mailtrap.io/) by creating a free account.

1. After signing in to Mailtrap, click on the __Demo Inbox__ link and look for your username and password under Credentials/SMTP.

1. Edit the `smtp.properties` file providing your username and password for your Demo Inbox as the values of the properties `SMTPAppender.smtpUsername` and `SMTPAppender.smtpPassword`, respectively.

1. Execute `mvn compile exec:java`.

1. Check your Demo Inbox on Mailtrap.
