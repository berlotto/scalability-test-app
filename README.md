Running on OpenShift
----------------------------

Create an account at http://getupcloud.com/

Create a PHP 5.5 application, and import all the quickstart codes:

    rhc app create <app name> php-5.5 cron-1.4 --from-code=https://github.com/berlotto/scalability-test-app.git

You can now checkout your RSS application at:

    http://<app name>-<your namespace>.getup.io


