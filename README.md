Mint.com is pretty great for viewing all of your budgets and finances in one place, but I was pretty annoyed with all of the ads and promotional links, so I created a filter list for ad blockers to hide these.

To add this list to uBlock Origin, open uBlock's settings page and click on the "Filter lists" tab.  At the bottom of the page, expand the "Custom" tree and check the "Import..." box.  Then, add this URL to the textarea that appears:

    https://raw.githubusercontent.com/synthead/mint-adfree/master/mint-adfree.txt

Click the "Apply changes" button on the top-left of the page, and you're done!  This URL reflects the latest commit to this list, so your ad blocker will auto-update accordingly.

This list can be used on all the other common ad blockers too, but they have their own settings page that I won't get into detail about.  If you don't know about [uBlock Origin](https://ublockorigin.com), you might consider switching to it as it's fast, light, and is [GPL-licensed](https://github.com/gorhill/uBlock/blob/master/LICENSE.txt).

Enjoy!

## TLDR Filters
You can use this to copy and paste into your favorite adblocker!
```
mint.intuit.com##li:has(> a[data-auto-sel="nav-marketplace"])
mint.intuit.com##li:has(> a[data-auto-sel="nav-incometaxhub"])
mint.intuit.com###marketplace-overview-cards
mint.intuit.com##div:has(> div[data-morpheus-pluginid="promotions-personalized-offers-ui"])
mint.intuit.com##div[class^="AccountsOverviewstyle__StyledLinksContainer-"]:has(a[href="/marketplace?task=savings"])
mint.intuit.com##div[class^="AccountsOverviewstyle__StyledLinksContainer-"]:has(a[href="/marketplace?task=cc"])
mint.intuit.com##div[class^="AccountsOverviewstyle__StyledLinksContainer-"]:has(a[href="/investment"])
mint.intuit.com##.promotions-personalized-offers-ui
mint.intuit.com##div[class^="BillNegotiationCollapsestyled__CollapseWrapper-"]
```
