# ZipStream
## Combine and stream the contents of multiple existing Zip files, as a single file, /without/ recompressing the data within.

This is useful if you have often used static content that needs to be collected and sent to the client.
With this you can pre-compress these packages, and assemble them on the fly, saving CPU cycles by not
having to do the compression every time the files are requested.

The contents of each Zip file added, can even be placed in separate sub folders.