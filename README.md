# Cyences-Input-Apps

This repository contains various input apps for Windows and Linux as listed below.

## Windows Input Apps:

* A-TA-ad_inputs
    * Addon Dependency: Splunk_TA_windows
    * Required Indexes: wineventlog, msad
* A-TA-dhcp_inputs
    * Addon Dependency: Splunk_TA_windows
    * Required Indexes: dhcp
* A-TA-dns_inputs
    * Addon Dependency: Splunk_TA_windows
    * Required Indexes: dns
* A-TA-windows_inputs
    * Addon Dependency: Splunk_TA_windows
    * Required Indexes: wineventlog, windows


## Linux Input Apps:

* A-TA-cyences_inputs
    * Addon Dependency: TA-cyences
    * Required Indexes: os
* A-TA-nix_inputs
    * Addon Dependency: Splunk_TA_nix
    * Required Indexes: os


**NOTES:**

* Ensure you look for the **Addon Dependency** and **Required Indexes** for each apps, meaning those apps and indexes has to be deployed before deploying these input apps.

* Ensure you look for `TODO` items inside `inputs.conf` before deploying to the environment.
