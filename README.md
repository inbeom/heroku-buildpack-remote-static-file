# Heroku Buildpack: Remote Static File

Fetches a remote file specified by URL and store it under build directory.

## Usage

  - Set URL of remote file to fetch to an environment variable named
    `REMOTE_STATIC_FILE_FROM`.
  - (Optional) Set local file name of the fetched remote file to an environment
    variable named `REMOTE_STATIC_FILE_TO`.
  - The file will be stored in `static` directory under your build directory.
