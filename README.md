# emby-swagger
Expanded Swagger File for Emby

By having a more accurate Swagger / OpenAPI 2.0 file for Emby, it becomes much easier to build high quality clients and applications. The auto-generated Swagger file only has a rough outline of available methods, and has almost no parameter or data definitions.

I've converted the file into YAML (I find it easier to work with), performed some cleanup, and added quite a bit of data definitions.

To try to make it clear which portions I've worked on (and which I've yet to look at), I've been added 'tags' to the methods that are complete. Thus, if an API has no tag (or falls into the DefaultApi [assuming your using Swagger Codegen]), then it's pretty much directly what came from the Emby code.

I am more than willing to incorporate changes/fixes. Either file an issue and/or open a pull request.

To help with versioning, I've included the original generated Swagger file beside the expanded one.