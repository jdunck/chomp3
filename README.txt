It turns out that MP3s encoded as data: URIs are useful - an URL shortener to a data: uri would allow tweeting of MP3s.

chomp3 aims to be a service to encode MP3s as URIs so they can be more easily shared.

====

S3 for cheap storage.
Running on EC2 for free S3/server transfer.
Uploader in Django, streaming that data: URI to S3.
Service using nginx for html and varnish for ESI of the wrapper.
fabric for deploy, chef for server config
