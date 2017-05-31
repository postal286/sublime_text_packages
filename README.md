# sublime_text_packages

This repository was created to save preferences and packages of text-editor sublime 3.
To complete install copy this object of parameters into user settings of sublime and put the other files into Packages derectory.
This setup contain following modules:
	"Emmet",
	"AutoFileName",
	"Gist",
	"Stylus",
	"One Dark Material - Scheme",
	"One Dark Color Scheme",
	"Buffer Scroll"	

{
	"font_size": 16,
	"show_definitions": false,
	"auto_complete": true,
	"bold_folder_labels": true,
	"color_scheme": "Packages/One Dark Material - Theme/schemes/OneDark.tmTheme",
	"fold_buttons": true,
	"highlight_line": true,
	"indent_guide_options":
	[
		"draw_normal",
		"draw_active"
	],
	"line_padding_bottom": 2,
	"line_padding_top": 2,
	"margin": 2,
	"material_theme_compact_sidebar": true,
	"material_theme_compact_pannel": true,
	"material_theme_small_statusbar": true,
	"material_theme_small_tab": true,
	"tab_size": 2,
	"theme": "OneDarkMaterial.sublime-theme",
	"word_wrap": "false",
	"ignored_packages":
	[
		"Vintage"
	]
}

Settings for auto-leveling text. Add this string into Key Binding config:

[
    { "keys": ["alt+shift+f"], "command": "reindent" },
]
