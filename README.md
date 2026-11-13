# yairo87.github.io

The developer website for echolessdev's Android apps, served by GitHub Pages at https://yairo87.github.io/. This is
the address to give as the website in each app's Play Store listing.

| Path | What it is |
| --- | --- |
| `index.html` | The home page: the apps and links to their privacy policies |
| `paintpour/privacy/index.html` | Paint Pour's privacy policy, at https://yairo87.github.io/paintpour/privacy/ |
| `app-ads.txt` | Not yet: the ad networks' seller lines, added once the AppLovin MAX account exists |

OffMyMind's privacy policy stays in its own repo, `yairo87/offmymind-privacy`, at
https://yairo87.github.io/offmymind-privacy/, the address its store listing already uses.

`app-ads.txt` has to sit at the root of the domain named as the website in the Play listing, which is why this site
is a user site (`yairo87.github.io`) and not a project page. `.nojekyll` makes Pages serve the files as they are.

When an app gains or drops an SDK, a permission or anything it stores or sends, change its policy and its
"Last updated" date in the same commit.
