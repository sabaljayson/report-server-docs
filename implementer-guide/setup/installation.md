---
title: Installation
page_title: Installation
description: Installation
slug: installation
tags: installation
published: True
position: 200
---

# Installation

The Report Server web application is installed by a Windows installer which automatically creates a separate web site with its own application pool on the IIS. The application pool runs under the *LocalSystem* identity and has *Enable 32-Bit Applications* set to *true* by default. Note that this setting might cause external entities like ODBC drivers to fail to work with Report Server due to architecture mismatch between the driver and the application.

The installer registers the new web site under port 83 by default. The installation process includes registering and starting of a Scheduler windows service.

## Downloading and Installing

You can download the licensed product version from the **Telerik Control Panel** which you can get from [Your Account](http://www.telerik.com/account). The Control Panel is a small Windows utility which will notify you when a new version of the Telerik product(s) you have purchased is available. Once you download the product, run the installer to install it on your machine.

## New Versions

The best way is to download the Control Panel from [Your Account](http://www.telerik.com/account/):

![control panel](../../images/report-server-images/control-panel.png)

It automatically detects the latest version and lets you install it for the products you have access to.

## Other Product Files and Latest Internal Builds

1. From [Your Account page](http://www.telerik.com/account/), go to “Products & Subscriptions” and select the product:
![latest internal build step 1](../../images/report-server-images/latest-internal-build.png)
2. Hit the "Download" button:
![latest internal build step 2](../../images/report-server-images/latest-internal-build-2.png)
3. From there select the product file you want to download:
![latest internal build step 3](../../images/report-server-images/latest-internal-build-3.png)
