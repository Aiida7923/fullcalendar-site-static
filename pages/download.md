---
permalink: /download
title: Download
layout: text
---

<div class='sidenote-layout'>
<div class='sidenote-layout__main' markdown='1'>

<h2>
  Latest:
  <a href='{{ site.fullcalendar_repo }}/releases/download/v{{ site.data.fullcalendar_latest.version }}/fullcalendar-{{ site.data.fullcalendar_latest.version }}.zip'
    onclick="ga('send', 'pageview', '/downloads/fullcalendar-{{ site.data.fullcalendar_latest.version }}.zip')"
    >fullcalendar-{{ site.data.fullcalendar_latest.version }}.zip</a>
</h2>

[Changelog + All Releases &raquo;]({{ site.fullcalendar_repo }}/releases)


## Package Managers

FullCalendar is available on [NPM](https://www.npmjs.com/) or [Yarn](https://yarnpkg.com/). [Follow the instructions &raquo;]({{ site.baseurl }}/docs/initialize-es6)


## CDN

A number of free CDNs host FullCalendar's dist files. A clever way to choose a CDN and figure out the URLs of the files you need is to visit the package on [Yarn](https://yarnpkg.com/). For example, visit the [@fullcalendar/core](https://yarnpkg.com/en/package/@fullcalendar/core) package. Then, look at the "CDNs" area on the sidebar.

You'll be manually initializing FullCalendar with [script tags and globals]({{ site.baseurl }}/docs/initialize-globals), so make sure you've included all the necessary files for whatever [plugins you choose]({{ site.baseurl }}/docs/plugin-index).

</div>
<div class='sidenote-layout__sidenote' markdown='1'>

### Looking for the Scheduler plugin?

[Visit the free-trial page]({{ site.baseurl }}/scheduler/download)

</div>
</div>
