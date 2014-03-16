Browser-Detection
=================

Because sometimes, you just want to know what the browser is.

Back-Story
=================

The good people over at JQuery decided that browser detection isn't the way to go. Their idea is that feature detection is the only way. So, $.browser was removed from JQuery 1.9 onwards. (Modernizr also doesn't support this).

Well, just peachy... I guess... Unless you want to provide a support page to clients telling them what they should already know - or one of the many other reasons you might want a quick way to see the browser type.

Quirks Mode came to the rescue with their own browser detection (http://www.quirksmode.org/js/detect.html). But alas, keeping it up to date was too hard. And so now recomments WhichBrowser (http://whichbrowser.net/)... but that seems to require PHP. Not ideal for everyone/ every situation.

While I was personally updating Quirks Mode's old code, I stumbed upon this code included in an update from (mb)Menu (http://pupunzi.open-lab.com/mb-jquery-components/mb-_menu/). This adds in the missing $.browser back into JQuery.

Ps: I've updated this below to better handle the change in User Agent with the newer Opera browsers (which reports as OPR, not Opera)

Permissions for use: As you would have read above, this is found in the (mb)Menu code. And I've not added any restrictions to it - so go nuts :)  (Pupunzi uses MIT and GPL v2 for the licencing.)

Btw: Pupunzi is great. Have a look at www.pupunzi.com - some great stuff going on there. :)
