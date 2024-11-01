``` javascript 
var script = document.createElement('script');
script.src = 'https://cdn.jsdelivr.net/gh/fuwt/resources@main/ks.js';
document.body.appendChild(script);
```

```  vimscript 
%s/(/（/g
%s/)/）/g
%s/\n\([^a-zA-Z0-9正].*\)/\1
%s/ \(正确答案.*\)/\r\1
%s/[^\n]\([B-Z]\.\)/\r\1/g
%s/\s//g
%s/（）/（ ）/g
%s/\*//g
%s/ //g
```
