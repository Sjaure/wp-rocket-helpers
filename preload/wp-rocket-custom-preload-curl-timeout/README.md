# Custom cURL Timeout For Preload Request

Increase the timeout for cURL from 5 seconds for preload request.

Helps resolve the issue where preload is stuck at zero with `cURL error 28: Operation timed out after 5000 milliseconds with 0 bytes received`.

To be used with:
* any setup that uses sitemap preload. 

Last tested with:
* WP Rocket 3.2.x
* WordPress 4.9.x
