**Extension**

https://www.sitepoint.com/create-chrome-extension-10-minutes-flat/

**Protocol**

https://support.shotgunsoftware.com/hc/en-us/articles/219031308-How-to-launch-external-applications-using-custom-protocols-rock-instead-of-http-
http://stackoverflow.com/a/37601807/2251068

```
Windows Registry Editor Version 5.00

[HKEY_CLASSES_ROOT\ytdl]
(Default) = “URL:ytdl Protocol Handler”
"URL Protocol"=""
[HKEY_CLASSES_ROOT\ytdl\shell]
[HKEY_CLASSES_ROOT\ytdl\shell\open]
[HKEY_CLASSES_ROOT\ytdl\shell\open\command]
@="mpv %1"
```

```
<input id="DealerName" />
<button id="PrintBtn"></button>

$('#PrintBtn').on('click', function(event){
  event.preventDefault();
  window.location.href = 'mycustproto:dealer ' + $('#DealerName').val();
});
```
