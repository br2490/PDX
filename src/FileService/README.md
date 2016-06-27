File Controller Conceptualization
=================================

* Should add files to filesets in an Object
* IF no fileset container exists, create one and report
* Be agnostic as to ontology, instead focus on `put` service for a binary and have `patch` available to accept addtl' fcr:metadata.
* Should return something if successful else panic.


Should accept
=============

* put/post file/{object} - creates pcdm:Object and attaches any binaries as pcdm:File. Object here hasMember, hasRelatedObj.
* patch file/{object} - append additional metadata.
* get file/{id} - do something.
* delete file/{object} - delete something.


pcdmuse?
========

* Nope. This service doesn't give a hoot.