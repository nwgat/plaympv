**Extension**

https://www.sitepoint.com/create-chrome-extension-10-minutes-flat/

**Protocol**

https://support.shotgunsoftware.com/hc/en-us/articles/219031308-How-to-launch-external-applications-using-custom-protocols-rock-instead-of-http-


cmdLine points to the foo path.

Add foo to the Os protocols and set foobar to handle the protocol

```
[HKEY_CLASSES_ROOT\ytdl]
@="URL:ytdl Protocol"
"URL Protocol"=""
[HKEY_CLASSES_ROOT\ytdl\shell]
[HKEY_CLASSES_ROOT\ytdl\shell\open]
[HKEY_CLASSES_ROOT\ytdl\shell\open\command]
@="\"mpv\" \"%1\""
```
