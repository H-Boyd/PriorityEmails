# Priority Email Bookmarklet

This bookmarklet streamlines the use of gmail by automatically applying the
filter:
`label:inbox | is:starred | is:unread | in:draft | label:meta-needs_attention | has:nouserlabels `

If you are already signed into gmail in the current window, this shortcut will
apply the filter to the profile in use.

To get this bookmarklet working, Right click on the toolbar and select new
bookmark, name the bookmark "Priority Emails" and then in the URL test box,
paste the entirety of PriorityEmails.js and press save.

To get the icon to work, make sure to go to `about:config` and set
`toolkit.legacyUserProfileCustomizations.stylesheets` to true.
then go to `about:support` and click open profile folder.
Then, if one does not exist already, create a folder named chrome.
In this chrome folder, copy across the Icons directory, and the userChrome.css
file. Then restart firefox, and any bookmark or bookmarklet named
"Priority Emails" should have the P icon.
