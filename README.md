BrowserMob Proxy
================
This is a fork of a fork of BrowserMob proxy with the added ability to capture response body with 
the contenttypes (i.e. with the HTTP-header "Content-Type: xxxx/yyy") specified.

Additional Usage info:
-------- 
(See  https://github.com/webmetrics/browsermob-proxy for other functionality) 

	//We need to capture the content ... 
    proxyServer.setCaptureContent(true);
	
	// These are the content types to be captured, note that this will 
	// capture all content that begins with the items in the list, 
	// so "text/html" will capture all html regardless of encoding
	// and "" will capture all content types.
		
    List <String> contentTypes  = Arrays.asList("application/xml", "text/html", "text/javascript", "text/css");
    ProxyServer.setCaptureContentTypes(contentTypes);



    	