WildforumsTheme
===============

Wildforums theme for 'Stylish' to be used on http://community.kabam.com/    
**Work in process**


####Get Stylish
#####[Stylish for  Chrome](https://chrome.google.com/webstore/detail/stylish/fjnbnpbmkenffdnngjfgmeleoegfcffe?hl=en)
#####[Stylish for Firefox](https://addons.mozilla.org/us/firefox/addon/stylish)

####How to use with Chrome?
Settings > Extensins > Stylish > Options > Write New Style > Copy the `style.css` to *Code* block > Applies to `URLS starting with` - `http://community.kabam.com/forums/` > Save

####How to use with FireFox?
Extensinons > Style > Write New Style > Copy (and read) this:
```css
@namespace url(http://www.w3.org/1999/xhtml);
@-moz-document domain("http://community.kabam.com/forums/"),
              url("http://community.kabam.com/forums/"),
              url-prefix("http://community.kabam.com/forums/")
{ 

/*
contents of style.css here 
yep, here
*/

} /*  remember to close the {} */

```

Save.


####Contribute

######Note: I'm not *css* person - be aware that it's heavily crappy code so far.






