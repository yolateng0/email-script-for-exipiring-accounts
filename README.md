# Script to Send eMail With a List of User Accounts Expiring in “X” Days

The password enforcement policy is common to all operating systems and applications.

If you want to implement a password enforcement policy on Linux, go to the following article.

The password enforcement policy will be enforced by most companies by default, but the time period will be different depending on the company’s requirements.

Usually everyone uses a 90-days password cycle.

The user will only change the password on some of the servers they use, and they won’t change the password on the servers they don’t use often.

In particular, most team forget to change the service account password, which can lead to breaking regular jobs even if they are configured to work with SSH key-based authentication.

SSH key-based authentication and cronjobs will not work if the user account password expires.

To avoid this situation, we have created a shell script that sends you a list of user accounts that expire within 10 days.

There are two bash scripts included in this tutorial that will help you collect information about user expiration days on your system.
