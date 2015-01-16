#Sublime Text3安装Package Control的命令

> https://packagecontrol.io
如果遇到无法通过Package Control安装插件的情况，很可能是因为sublime.wbond.net被Fire了，需要在host你添加以下IP

```
50.116.34.243 sublime.wbond.net
```

#我的Sublime Text3配置文件

```
{
	"bold_folder_labels": true,
	"color_scheme": "Packages/Theme - Spacegray/base16-ocean.dark.tmTheme",
	"draw_white_space": "all",
	"ensure_newline_at_eof_on_save": true,
	"folder_exclude_patterns":
	[
		"AppCode",
		"bin",
		"Properties",
		"obj",
		"debug",
		"App_Start",
		"Models",
		"Controllers",
		".svn",
		".git",
		".hg",
		"CVS"
	],
	"file_exclude_patterns" : ["*.cs", "*.config", "*.asax", "*.csproj", "*.csproj.user", "*.sln", "*.suo"],
	"font_face": "Source Code Pro",
	"font_options":
	[
	],
	"font_size": 14,
	"highlight_line": true,
	"highlight_modified_tabs": true,
	"ignored_packages":
	[
		"Vintage"
	],
	"line_padding_bottom": 1,
	"line_padding_top": 1,
	"scroll_past_end": true,
	"tab_completion": false,
	"tab_size": 4,
	"theme": "Spacegray.sublime-theme",
	"translate_tabs_to_spaces": true,
	"trim_trailing_white_space_on_save": true,
	"vintage_start_in_command_mode": true,
	"word_wrap": true
}

```

#常用插件列表

- emmet 神器，不解释
- alignment 强迫症患者
- Docblockr 原来注释也可以这么有艺术
- JsFormat JS格式化
- SideBarEnhancements 不多解释了吧，光是Preview in Browers就足够有理由装上了
- IMESupport 国人必备，不然输入法无法跟随光标

#参考资料

- Sublime Text 全程指引 http://www.cnblogs.com/figure9/p/sublime-text-complete-guide.html
- 打造一款便携版的Sublime Text http://segmentfault.com/blog/miraclewong/1190000000707661
