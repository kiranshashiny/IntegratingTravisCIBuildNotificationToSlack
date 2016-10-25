#### IntegratingTravisCIBuildNotificationToSlack

##### How to notify the slack channel about the Travis CI build status.

Typically, the Travis CI builds get completed and one has to watch the Travis CI build page to get information on the build status.


In this blog I will write about how to integrate the Slack channel so that the Travis notifies the channel on the build completion.

It is as easy as add a single line into the .travis.yml.

https://docs.travis-ci.com/user/notifications/#Slack-notifications

Click on "new Travis CI Integration" and follow the steps as listed.

Add the line to your .travis.yml and re-run the build.

<img width="943" alt="screen shot 2016-10-25 at 5 39 58 pm" src="https://cloud.githubusercontent.com/assets/14288989/19685453/574ba802-9ada-11e6-8c6a-07756f51d464.png">

<img width="1087" alt="screen shot 2016-10-25 at 5 39 50 pm" src="https://cloud.githubusercontent.com/assets/14288989/19685452/573169ec-9ada-11e6-926b-cac54dd0f131.png">

<img width="843" alt="screen shot 2016-10-25 at 5 39 37 pm" src="https://cloud.githubusercontent.com/assets/14288989/19685451/572b661e-9ada-11e6-8f0f-55dbf7bd1134.png">

On completion of the build - you should see the notification.

<img width="1033" alt="screen shot 2016-10-25 at 5 42 39 pm" src="https://cloud.githubusercontent.com/assets/14288989/19685476/7701bfc4-9ada-11e6-87e3-9041fb3e6e08.png">
