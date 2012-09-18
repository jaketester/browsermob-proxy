BrowserMob Proxy
================
This is a fork of a fork of BrowserMob proxy with the added ability to capture response body with 
the contenttypes set  

Usage:

ProxyServer.setCaptureContent();

List <String> contentTypes  = Arrays.asList("application/json", "text/html", "text/javascript", "text/css");

ProxyServer.setCaptureContentTypes(contentTypes)

