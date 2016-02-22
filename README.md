# Komik

**Komik** is a webcomic theme for the Ghost blogging platform.

[<img src="/screenshot.png?raw=true" width="400">](/screenshot.png?raw=true)

## Installation

This theme works with **Ghost 0.7.4** or newer. You also need to **enable the [Public Beta API](http://support.ghost.org/public-api-beta/)**. This is a checkbox at the bottom of your blog's `Settings` page.

If you are using [Ghost.org](http://ghost.org)'s Pro platform, follow the instructions at [the Ghost support page](http://support.ghost.org/upload-theme-ghostpro/).

If you are using a Ghost installation in your own server, follow these steps.

1. Go to the [releases page](https://github.com/belen-albeza/komik-theme/releases) and download the latest release.
2. If you are hosting your own Ghost installation, unzip the tarball file into `content/themes/`.
3. Restart Node. How you do this will depend on your actual server setup.
4. Login into your blog, go to `Settings` and pick up `komik-theme` from the `Theme` dropdown.

## How to use

### Publish comics

This theme assumes that you create a new post per comic strip / page. You also **must use the `featured image`** setting in your post to upload your picture. You get to this setting by clicking the "gear" icon while editing a post. See this picture:

![Featured image setting](/howto.png?raw=true)

### Create an archive

This themes can show an **archive** with a list of all the comics that have been published.

To do that, you just need to [create a static page](http://support.ghost.org/publish-a-static-page/) and **set `comic-archive` as its slug** (the `Post URL` field).

![Archive settings](/howto_archive.png?raw=true)

In order for this archive page to show up in the menu, you need to [add it to the navigation menu](http://support.ghost.org/add-navigation-menu-ghost-blog/). The URL will be `http://yourdomain.com/comic-archive`. As the title for that menu item you can put whatever you like! Here `Archive` has been used.

![Navigation settings](/howto_navigation.png?raw=true)

## Configuration

This theme ignores the following:

- The "post per page" setting. It will only display one strip at a time in the main page.
- Tags will not be displayed.
- Featured post will not have a special treatment.
- Blog cover and blog logo (_might_ be taken into account in future releases)

Right not there is nothing to configure, besides what you can normally do.

## Changelog

- **1.1.1**
    - Fixed wrong order in the archive list.
- **1.1**
    - Added a page template that outputs the archive of comics
- **1.0.1**
    - Fixed broken layout on mobile devices
- **1.0.0**
    - First version
