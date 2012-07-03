---
layout: post
title: "Bolded folder names in Sublime Text 2"
date: 2012-07-03 09:56
comments: true
categories: [Sublime Text 2]
---

By now you probably have heard about Sublime Text 2. Great editor, and my personal favorite. One of the biggest downfalls, in my opinion, of ST2 is the sidebar. You should install [SideBarEnhancements][1] to get started, but that doesn't fix some of the UI scanning issues in large projects. 

Making folder names bold, as per TextMate helps the situation a little bit. This little known features was added in [Build 2195][2] on April 16th.

<!-- more -->

Start by opening your configuration file. You can quickly access it by typing `CMD + ,`

Add the following line:
`"bold_folder_labels": true`

**Boom!**

I've attached my config file in case people are interested.

``` json Sublime Text 2 Configuation File
{
	"auto_complete_commit_on_tab": true,
	"caret_style": "phase",
	"color_scheme": "Packages/Color Scheme - Default/Tomorrow-Night.tmTheme",
	"draw_minimap_border": false,
	"fade_fold_buttons": false,
	"find_selected_text": true,
	"font_face": "Inconsolata-Dz",
	"highlight_modified_tabs": true,
	"bold_folder_labels": true,
	"font_options":
	[
		"subpixel_antialias"
	],
	"font_size": 13.0,
	"highlight_line": true,
	"indent_to_bracket": true,
	"line_padding_bottom": 3,
	"overlay_scroll_bars": "enabled",
	"scroll_speed": 5.0,
	"shift_tab_unindent": true,
	"tab_size": 2,
	"translate_tabs_to_spaces": true,
	"use_simple_full_screen": true
}
```

[1]: https://github.com/titoBouzout/SideBarEnhancements/
[2]: http://www.sublimetext.com/dev