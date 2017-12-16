Simple-RasPlex-Remote
=====================
Created by: Michael Page


Control RasPlex from any device with a web browser.

Usage:

* Load remote.html in your web browser.
* Enter the IP address of the RasPlex instance into the 'Server hostname or IP address' field.

Troubleshooting:

* If it doesn't work, that means the IP address is not reachable on port 3005. You can test this by visiting `http://<IP address>:3005/resources`. This should yield an XML document that describes the RasPlex instance.
