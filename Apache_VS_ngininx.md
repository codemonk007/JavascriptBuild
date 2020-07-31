Apache
*   Apache runs on all Unix like systems such as Linux, BSD, etc. as well as completely supports Windows.	

*   Apache uses a multi-threaded approach to process client requests.	

*   Apache cannot handle multiple requests concurrently with heavy web traffic.	

*   Apache processes dynamic content within the web server itself.	

*   Apache is designed to be a web server.	

*   Modules are dynamically loaded or unloaded, making it more flexible.	Since           modules cannot be loaded dynamically, they must be compiled within the core             software itself.

*   The performance of Apache for static content is lower than Nginx.	

    
###NGinix
*   Nginx runs on modern Unix like systems; however it has limited support for Windows.

*   Nginx follows an event-driven approach to serve client requests.

*   Nginx can handle multiple client requests concurrently and efficiently with limited     hardware resources.
*   Nginx can't process dynamic content natively.

*   Nginx is both a web server and a proxy server.

*   A single thread can only process one connection.	A single thread can handle          multiple connections.

*   Nginx can simultaneously run thousands of connections of static content two times       faster than Apache and uses little less memory.
