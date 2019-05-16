# non_functional_functions
Using firebase tools version 3.18.6 this repo was created with firebase init functions.

to deploy:

`npm install`

`firebase deploy`

Getting the following 400: 

`<<< HTTP RESPONSE 400 vary=X-Origin, Referer, Origin,Accept-Encoding, content-type=application/json; charset=UTF-8, date=Thu, 16 May 2019 01:47:26 GMT, server=ESF, cache-control=private, x-xss-protection=0, x-frame-options=SAMEORIGIN, x-content-type-options=nosniff, alt-svc=quic=":443"; ma=2592000; v="46,44,43,39", accept-ranges=none, connection=close
 [2019-05-16T01:47:26.660Z] <<< HTTP RESPONSE BODY code=400, message=The request has errors, status=INVALID_ARGUMENT, details=[@type=type.googleapis.com/google.rpc.BadRequest, fieldViolations=[field=runtime, description=Runtime field cannot be empty.]]
`

-And this is the resulting output:

![alt text](./functions/Screen%20Shot%202019-05-15%20at%209.43.31%20PM.png)
