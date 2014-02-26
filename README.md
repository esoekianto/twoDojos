About this "TwoDojos" Sample
=============================

This sample is intended to demonstrate the workaround when there is a default setting of dojo in the page. 

Ideally we want the user to use the dojo version that comes with our javascript API, but if it is not possible, this is how we work around it, as shown in the sample.

For example, when using our javascript API in Portlet in IBM Websphere, where the portlet runtime set to use dojo version 1.7, error 404 not found will appear when page is trying to load the resources from the default dojo in portlets instead of our API.

This sample is modified from here, https://developers.arcgis.com/javascript/jssamples/map_simple.html
