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

Don't mess with the context menu (hint: Shift+Right click does the same thing)

```
dom.event.contextmenu.enabled: false
```

Websites use light CSS theme (don't report actual system/firefox theme)

```
ui.systemUsesDarkTheme: 0
```

Use light gtk theme

```
widget.gtk.alt-theme.dark: 	false
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

Zooming steps for `ctrl +/-` and toolbar controls

```
toolkit.zoomManager.zoomValues: .3,.4,.5,.6,.7,.8,.9,1,1.1,1.2,1.3,1.4,1.5,1.6,1.7,1.8,1.9,2,2.1,2.2,2.3,2.4,2.5,2.6,2.7,2.8,2.9,3,3.1,3.2,3.3,3.4,3.5,3.6,3.7,3.8,3.9,4,4.1,4.2,4.3,4.4,4.5,4.6,4.7,4.8,4.9,5
```

# Legacy

https://bugzilla.mozilla.org/show_bug.cgi?id=1522083

https://addons.mozilla.org/en-US/firefox/addon/dont-touch-my-tabs/

```
dom.targetBlankNoOpener.enabled: true
```
