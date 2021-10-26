# http-server-upload

> Zero-configuration command-line HTTP server which provides a lightweight interface to upload files.
> More information: <https://github.com/crycode-de/http-server-upload>.

- Start a HTTP server in the default port to upload files in the current directory:

`http-server-upload`

- Start a HTTP server with the specified maximum allowed file size for uploads in MiB (defaults to 200 MiB):

`MAX_FILE_SIZE={{size_in_megabytes}} http-server-upload`

- Start a HTTP server in a specific port to upload files in the current directory:

`PORT={{port}} http-server-upload`

- Start a HTTP server storing the uploaded files into a specific directory:

`UPLOAD_DIR={{path/to/directory}} http-server-upload`

- Start a HTTP server using a specific directory to storing files during upload:

`UPLOAD_TMP_DIR={{path/to/directory}} http-server-upload`

- Start a HTTP server accepting uploads with a specific token in the header:

`TOKEN={{secret}} http-server-upload`