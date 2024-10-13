# Caddy browse Kodi template

This template is designed to mimmick the directory listing behaviour of Nginx for the use of Kodi directory listing.

Tested on Caddy v2.8.4 running in Docker under Debian Linux 12.

Example use:

```
files.yoursite.com {
  root * /path/to/your/stuff
  file_server {
    browse /path/tp/your/teplate/kodi-browse.tpl
  }
}
```

# Known issues

- Needs improvement of spacing between filenames and datestamp.
