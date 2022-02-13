# Implementation-of-Proxy-Cache-Server
<li>Created a proxy server that stores content on the proxy server itself and allows web services to share those resources to more users. 
<li>Proxy server acts as a gateway between the user and the source server, storing (or caching) the servers and clients resources. 
<li>The cache information can be used for business and marketing. Also, blacklisting some domains can also be performed using the cache information.
<li>Proxy_cache - Implementation of proxy cache server using linked lists.
<li>Proxy_cache_server - Implementation of proxy server where the client requests are captured and request the same url to http server and provide teh information to the client back. If the client request for same url, then the data will be fetched using the cache information.
<li>Proxy_cache_client, web_client - Client requests for some url to the main server.
<li>web_proxy - Implementation of cache server using dictionary.
