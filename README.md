# Joplin - Milford UI

_joplin-milford-ui_ is a theme to adapt the UI of [Joplin's](https://joplinapp.org/) desktop application.

> **Visit [Milford Sound](https://www.newzealand.com/int/milford-sound/) in New Zealand! :heart_eyes:**

> :warning: **CAUTION** - This theme requires at least version **v1.4.10**

## Table of contents

- [Features](#features)
- [Screenshots](#screenshots)
- [Installation](#installation)
- [UI tweaks](#ui-tweaks)
- [Feedback](#feedback)
- [Changes](#changes)
- [License](#license)

## Features

This theme changes the following parts of the user interface.

// TODO
- Colored tags
- Cleaner note list including floating plus button to create new notes/to-dos
- Floating editor toolbar at the bottom of the editor content
  - Not supported for TinyMCE
- Local search inlined with tag list
- Improved style of panel splitters
  - Highlighted while dragging
- Changed style of synchronize area and button
- Decreased visibility of toolbar icons
  - To focus more on content
- Floating TOC on the right for rendered Markdown mode
  - Based on the idea from [here](https://discourse.joplinapp.org/t/toc-as-the-sidebar/5979/34)
  - Requires `[[toc]]` in note content
- Show/hide line numbers in CodeMirror
  - Based on the idea from [here](https://discourse.joplinapp.org/t/option-to-show-line-numbers-in-editor/8313/22)
- Changed visibility of some UI elements by default
  - Can be adapted manually - see [UI tweaks](#ui-tweaks)

> **Works with all built-in color themes**

## Screenshots

// TODO create screenshot

![Dark Theme](./assets/main.png)

## Installation

- Open Joplin
- Navigate to `Joplin > Preferences > Appearances`
- Click `Advanced Settings`
- Click `Custom stylesheet for rendered Markdown` and paste the content from [userstyle.css](./theme/userstyle.css)
- Click `Custom stylesheet for Joplin-wide app styles` and paste the content from [userchrome.css](./theme/userchrome.css)
- Save your changes and restart Joplin to see the changes

## UI tweaks

- Open Joplin
- Navigate to `Joplin > Preferences > Appearances`
- Click `Advanced Settings`
- Click `Custom stylesheet for rendered Markdown` to open `userstyle.css` in any text editor
- Click `Custom stylesheet for Joplin-wide app styles` to open `userchrome.css` in any text editor
- Search for `TWEAK` and change the styles as described if you want
- Save your changes and restart Joplin to see the changes

## Feedback

If you need help or found a bug, open an issue on [GitHub](https://github.com/benji300/joplin-milford-ui/issues).

## Changes

See [CHANGELOG](./CHANGELOG.md) for details.

## License

Copyright (c) 2020 Benjamin Seifert

MIT License. See [LICENSE](./LICENSE) for more information.