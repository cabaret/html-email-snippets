sublime-html-email-snippets
===========================

Snippets to help create HTML emails quicker.


Install using Package Control or clone the repository to `~/Library/Application Support/Sublime Text 2/Packages/User`


This gives you access to a couple of tab triggers: `mlreset`, `mltable`, `mltd`, `mlimg`, `mla`.


`mlreset` will expand into:
```
 <style type="text/css">
    /* Client-specific Styles */
    #outlook a{padding:0;} /* Force Outlook to provide a "view in browser" button. */
    body{width:100% !important;} .ReadMsgBody{width:100%;} .ExternalClass{width:100%;} /* Force Hotmail to display emails at full width */
    body{-webkit-text-size-adjust:none; -ms-text-size-adjust:none;} /* Prevent Webkit and Windows Mobile platforms from changing default font sizes. */
  
    /* Reset Styles */
    body{margin:0; padding:0;}
    img{height:auto; line-height:100%; outline:none; text-decoration:none;}
    #backgroundTable{height:100% !important; margin:0; padding:0; width:100% !important;}
  
    </style>
```

`mltable` will expand into `<table cellspacing="0" cellpadding="0" align="left" border="0" width="100%">`

`mltd ` will expand into `<td valign="top" align="left" width="">`

`mlimg` will expand into `<img src="" alt="" style="display: block; outline; none; border: none;" />`

`mla` will expand into `<a href="" title="" style="display: block; text-decoration: none; outline: none; border: none;"></a>`

Tabstops have been implemented where needed.

Suggestions welcome.
