taylr
=====

A Chrome extension to replace the Tumblr logo with Taylr. I got the idea from the Taylor Swift fan community on Tumblr, and I built this for them.

Tumblr on Chrome will then look like

<img src="images/screenshot_dashboard_original.png?raw=true" width="300" >

<img src="images/screenshot_login_original.png?raw=true" width="300" >

You can download it [here](https://chrome.google.com/webstore/detail/taylr/fgcdbepnkehbeidckjkjphjpkkibejne).

It's pretty basic. I just override the css rules for the logo (using !important) so that they load a modified version of the tumblr logo on the dashboard and the homepage. Eventually I should do something more intelligent so it handles when Tumblr does random stuff with their logo, but for now this works.
