# ng-kaltura-player
## Overview
A directive for [AngularJS](http://angularjs.org) for embedding the [Kaltura](http://www.kaltura.com) video player.<br/>
The directive supports basic embedding as well an API for controlling the player using notifications and events registration.<br/>
Player plugins can be configured as well.
## Setup
1. Download the directive file: ng-kaltura-player.js and add it to your HTML page.
```
&lt;script src=&quot;ng-kaltura-player.js&quot;&gt;&lt;/script&gt;
```
2. Inject the 'Kaltura.directives' namespace to your Angular application
```
angular.module('App', ['Kaltura.directives'])
```
3. Use the directive in your HTML markup
```
&lt;kaltura-player width=&quot;640px&quot; height=&quot;320px&quot;&gt;&lt;/kaltura-player&gt;
```
4. Explore the example below to learn how to configure the player and use its API
## Examples
 * Basic player
 * Multiple players on the same page
 * Passing a Flashvar object for plugins configuration
 * Sending notifications to the player
 * Registering and un-registering to player events