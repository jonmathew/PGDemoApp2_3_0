PGDemoApp2_3_0
==============

Setting a up a new PhoneGap project in Eclipse with Git as VCS in 10 steps and 30 minutes
-----------------------------------------------------------------------------------------

Create a new LOCAL Git-repo with GfW

Create a new PG project in Eclipse with the Applaud Plugin

Follow the wizard, rename cordova-2.x.js libraries to *.<NO js as extension!>
  <!-- ========================================================================= -->
	<!-- Copy this block to your next 2nd,3rd PhoneGap project for saving time.... -->
	<!-- ========================================================================= -->
	<link rel="stylesheet" href="assets/www/jquery.mobile/jquery.mobile-1.3.0-beta.1.css" />
	<link rel="stylesheet" href="assets/www/docs/assets/css/jqm-docs.css" />
	<link rel="stylesheet" href="assets/www/docsdemos-style-override.css" />
	<script type="text/javascript" src="assets/www/jquery.mobile/jquery.mobile-1.3.0-beta.1.minjs"></script>
	<!-- Uncomment following line to access PhoneGap APIs (not necessary to use PhoneGap to package web app) -->
	<script type="text/javascript" charset="utf-8" src="assets/www/cordova-2.3.0.js"></script>
	<!-- =======================End of cordova 2.x.x block ======================= -->

Adjust references to those libraries....test in Emuator. If working without serious errors go build it with build.phongap

Close project and delete it.

Move project to new LOCAL Git-repo, and publish all to Github....

Go back to Eclipse and use the import wizard. File > Import > Git > Projects from Git > Local > Select a repo > Import existing projects (recommended in documentation) and import the project found

Go to https://build.phonegap.com/apps and paste in https://github.com/plankenw/PGDemoApp2_3_0.git

After build scan QR code with QR Droid an install on your phone.

Have fun testing it...
