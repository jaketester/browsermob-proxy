BrowserMob Proxy
================
This is a fork of a fork of BrowserMob proxy with the added ability to capture response body with 
the contenttypes specified.

Additional Usage info:
-------- 
(See  https://github.com/webmetrics/browsermob-proxy for other functionality) 

	//We need to capture the content ... 
    proxyServer.setCaptureContent(true);
	
	// This are the content types we want to capture, note that we will 
	// capture all content that begins with the items in the list, 
	// so "text/html" will capture all html regardsless of encoding.
	// and "" will capture anything...
		
    List <String> contentTypes  = Arrays.asList("application/xml", "text/html", "text/javascript", "text/css");
    ProxyServer.setCaptureContentTypes(contentTypes);



    	