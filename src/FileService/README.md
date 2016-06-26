Thoughts on file controller
==

* Should create a collection if one is not provided. Return collection UUID in response requesting PATCH (update).
* Should require PCDM in ttl.
* Should be universal


Should accept (following Danny's PorkPie in some respect)
==

* put/post file/{object} - creates pcdm:Object and attaches any binaries as pcdm:File. Object here hasMember, hasRelatedObj.
* patch file/{object} - append additional binaries?
* delete file/{object} - delete.


pcdmuse?
==

* put preservationFile/{object} - adds a file with PCDM and RDF that sets it as PM.
* put thumbnailFile/{object} - ' ' set as thumbnail.
* etc.