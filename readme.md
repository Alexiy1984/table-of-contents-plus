# Fork for Table of Contents Plus
Digestive health site, Guthack.com

## What's changed
1. Added position `NONE` : automatically generated TOC is not displayed on the page (to prevent duplication of TOC)
2. Added new setting for administrator menu `Show_comments` : to add a link for the comments at the bottom of toc

##You can add the plug-in automatically through the [composer](https://getcomposer.org/)

for this, edit your composer.json

```json
"repositories": [
    { "type": "composer", "url": "https://wpackagist.org"},
    {
      "type": "package",
      "package": {
        "name": "table-of-contents-plus",
        "version": "1.0",
        "source": {
            "url": "https://github.com/Alexiy1984/table-of-contents-plus.git",
            "type": "git",
            "reference": "master"
        }
      }
    }
  ],
  "require": {
    ...
    "composer/installers": "^1.4",
    "table-of-contents-plus": "1.0",
    ...
  },
  ```
  ##More information about the original plugin

  https://github.com/projectestac/wordpress-table-of-contents-plus

  https://ru.wordpress.org/plugins/table-of-contents-plus/

  https://dublue.com/plugins/toc/
