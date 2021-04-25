Don't close the window after the last tab is closed

```
browser.tabs.closeWindowWithLastTab: false
```

Place new tabs to the last position

```
browser.tabs.insertAfterCurrent: false
browser.tabs.insertRelatedAfterCurrent: false
```

---

Don't mess with the context menu

```
dom.event.contextmenu.enabled: false
```

Websites use light CSS theme (don't report actual system/firefox theme)

```
ui.systemUsesDarkTheme: 0
```

Disable remote fonts

```
gfx.downloadable_fonts.enabled: false
```

---

Don't trim "http://" prefix from url bar.

```
browser.urlbar.trimURLs: false
```

http://kb.mozillazine.org/Network.IDN_show_punycode

```
network.IDN_show_punycode: true
```

Urlbar suggestions

```
browser.urlbar.suggest
```

---

Enable custom blocklist selection in the preferences

```
browser.contentblocking.customBlockList.preferences.ui.enabled: true
```

Show compact mode in the customisation menu

```
browser.compactmode.show: true
```

Disable menu when alt key is pressed

```
ui.key.menuAccessKeyFocuses: false
```

---

Enable userchrome support

```
toolkit.legacyUserProfileCustomizations.stylesheets: true
```

# Legacy

https://bugzilla.mozilla.org/show_bug.cgi?id=1522083

https://addons.mozilla.org/en-US/firefox/addon/dont-touch-my-tabs/

```
dom.targetBlankNoOpener.enabled: true
```
