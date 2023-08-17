# Windows-Input-Apps
Inputs App for Windows to create various types of inputs like AD specific, DNS specific, DHCP specific and generic


* All of the Apps here has Splunk_TA_windows Add-on as dependency, meaning it has to be deployed along side any of these Apps.

* Ensure you look for `TODO` items inside `inputs.conf` before deploying to the environment.

* `TA-ad_inputs` only collects AD specific data, which means to collect the generic windows data you also have to deploy `TA-windows_inputs` app. And so on for other apps.

* Following indexes are required for these Apps. (dns and dhcp index are only require if you are deploying those Apps)
    * windows
    * wineventlog
    * msad
    * dns
    * dhcp
