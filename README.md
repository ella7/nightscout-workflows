# Nightscout Workflows

[Workflow] is an iOS app that allows you to create automated workflows from your phone or iPad. Nightscout Workflows is a collection of these workflows designed to make reading and writing information to and from Nightscout, and CarePortal in particular, as simple and painless as possible.

### Installation
You first need to make sure Workflow is installed on your device. 

[Get Workflow App]

Click on one of the links below to get the desired workflow. Workflow will ask for a few inputs (i.e.: your Nightscout URL). You can make additional customizations and configurations from within the app. You must click on the link(s) below from within Safari. If you're coming from Facebook, use the "open this page in Safari" option before clicking on the link(s) below. 

##### New
 - Added workflow to log pump site change events
 - In previous versions it was necessary to enter your hashed API secret. This is no longer the case. Just enter your normal Nightscout API secret that you used when you setup Nightscout.
 - Previously you needed to add /api/v1/treatments.json to the end of your Nightscout URL. This is no longer the case.

### Workflows
 - [Meter BG] Simple workflow to enter a metered blood glucose value and save to CarePortal.
 - [Change Site] Log a pump site change to CarePortal.
 - [Enter Carbs] Enter carbs in CarePortal for a specified time.


### Todos

 - Lots - just getting started
 - Add several other workflows. Suggestions are welcomed, so please feel free to submit issues. Pull requests are even better.
 - Add screenshots to README
 - Add instructions and screenshots for adding a workflow to your homescreen, to the today widget, and to Apple Watch. 


License
----
Apache 2.0

[Workflow]: http://workflow.is/
[Get Workflow App]: http://workflow.is/download
[OpenAPS Documentation]: http://openaps.readthedocs.io/en/latest/docs/Customize-Iterate/ifttt-integration.html#ifttt-setup-for-phones
[Meter BG]: https://github.com/ella7/nightscout-workflows/raw/master/workflows/Meter%20BG.wflow
[Change Site]: https://github.com/ella7/nightscout-workflows/raw/master/workflows/Change%20Site.wflow
[Enter Carbs]: https://github.com/ella7/nightscout-workflows/raw/master/workflows/Enter%20Carbs.wflow