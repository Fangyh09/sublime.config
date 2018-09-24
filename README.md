# sublime.config
My config for sublime
```json
[
	{ "keys": ["super+shift+u"], "command": "split_selection_into_lines" },
	{ "keys": ["super+d"], "command": "duplicate_line" },
	{ "keys": ["ctrl+d"], "command": "find_under_expand" },
	{
		"keys": ["ctrl+7"],
		"command": "insert_snippet",
		"args": {
			"contents": "console.log(${1:}$SELECTION);${0}"
		}
	},
	{ "keys": ["super+w"], "command": "expand_selection", "args": {"to": "scope"} },

]
```
