---
layout: default
title: Home
nav_order: 1
description: "KiwiChat NextClient WordPress Plugin."
permalink: /
---

<button class="btn js-toggle-dark-mode">Preview dark color scheme</button>

<script>
const toggleDarkMode = document.querySelector('.js-toggle-dark-mode');

jtd.addEvent(toggleDarkMode, 'click', function(){
  if (jtd.getTheme() === 'dark') {
    jtd.setTheme('light');
    toggleDarkMode.textContent = 'Preview dark color scheme';
  } else {
    jtd.setTheme('dark');
    toggleDarkMode.textContent = 'Return to the light side';
  }
});
</script>

# KiwiChat NextClient WordPress plugin
{: .fs-9 }

Try the new IRC KiwiChat WordPress plugin that works! based on kiwiirc nexclient, with 6 new themes

KiwiChat is an online chat client, your IRC client based on kiwiirc Add your networks. Join your channels.
{: .fs-6 .fw-300 }

[View it on GitHub](https://github.com/KiwiChat/wp-kiwichat){: .btn .btn-primary .fs-5 .mb-4 .mb-md-0 .mr-2 } [View it on WordPress](https://wordpress.org/plugins/kiwichat/){: .btn .fs-5 .mb-4 .mb-md-0 }

---

## Description

How to use KiwiChat…
Finally there is an IRC plugin for WordPress that works!
KiwiChat is an online chat client, your IRC client based on kiwiirc Add your networks. Join your channels.
To use this plugin:
1. simply download and extract it into your plugins folder
2. configure your settings in the WordPress dashboard
3. then drop the short tag ```[kiwichat]``` into your page or post.
Instantly your users will be able to stay connected via IRC.

## Installation

1. Upload the ```kiwichat``` folder to the ```/wp-content/plugins/``` directory.
2. Activate the plugin through the ```Plugins``` menu in WordPress.
3. Place ```[kiwichat]``` shortcode in your pages or posts.
4. You can specify channel for a specific page instead of using the default channel configured with: ```[kiwichat chan=#WebChat]```


## Download

[![Download KiwiChat Plugin][image]][hyperlink]

  [hyperlink]: https://wordpress.org/plugins/kiwichat/
  [image]: https://kiwichat.github.io/assets/images/kiwichat-300x150.png
  
 ---
 
## Screenshots

![Plugin configuration](https://raw.githubusercontent.com/KiwiChat/wp-kiwichat/master/assets/screenshot-1.png "Plugin configuration options page")

---

![Capture KiwiChat Home Screen](https://raw.githubusercontent.com/KiwiChat/wp-kiwichat/master/assets/screenshot-2.png "Capture KiwiChat Home Screen")

---

![Capture KiwiChat Online Chat](https://raw.githubusercontent.com/KiwiChat/wp-kiwichat/master/assets/screenshot-3.png "Capture KiwiChat Online Chat")

---

![KiwiChat Connected In Chat](https://raw.githubusercontent.com/KiwiChat/wp-kiwichat/master/assets/screenshot-4.png "KiwiChat Connected In Chat")
  
---

### Current stable version of the plugin ```6.0```
### Last update ```30/08/2022```

### License

KiwiChat is distributed by an [GPLv3 or later](http://www.gnu.org/licenses/gpl-3.0.html).
