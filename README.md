# chromebookBypasser
a repository to bypass chromebook stuff :yay:

## bypassing stuff


1. GoGuardian
- https://tinyurl.com/goofguardian
- Click link on that page
- Run this bookmarklet on the new blank page:

```javascript:for(var whar=confirm("ok = disable gg\ncancel = enable gg"),i=0;i<localStorage.length;i++)localStorage[localStorage.key(i)]=whar?%22-%22:%22%22;opener.chrome.extension.getBackgroundPage().location.reload()```


2. Cisco Umbrella
- https://tinyurl.com/goofumbrella
- Click link on that page
- Run this bookmarklet on the page:

```javascript:opener.chrome.extension.getBackgroundPage().close()```
