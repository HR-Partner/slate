# Errors


The HR Partner API may return the following error codes:


Error Code | Meaning
---------- | -------
400 | Bad Request -- Your request is invalid.
401 | Unauthorized -- Your API key is wrong.
403 | Forbidden -- The resource requested is not available to you.
404 | Not Found -- The specified resource or path could not be found.
405 | Method Not Allowed -- You tried to access a resource with an invalid method.
406 | Not Acceptable -- You requested a format that isn't JSON.
410 | Gone -- The resource you requested has been removed from our servers.
418 | I'm a teapot.
429 | Too Many Requests -- You're requesting too many things at once! Slow down!
500 | Internal Server Error -- We had a problem with our server. Try again later.
503 | Service Unavailable -- We're temporarily offline for maintenance. Please try again later.
