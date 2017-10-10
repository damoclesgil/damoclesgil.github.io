# My Workspace In VSCODE

## USER SETTINGS
````json
{
    "workbench.colorTheme": "Atom One Dark",
    "window.zoomLevel": 3,
    "git.confirmSync": false,
    "workbench.iconTheme": "vscode-icons",
    "vsicons.projectDetection.autoReload": true,
    "editor.minimap.enabled": false,
    "files.autoSave": "onWindowChange",
    "workbench.activityBar.visible": true,
    "liveServer.settings.donotShowInfoMsg": true,
    "editor.fontFamily": "Operator Mono Light, sans-serif",
    "editor.fontSize": 12,
    "html.format.unformatted": "head, /html",
    "workbench.colorCustomizations": {
        "statusBar.background": "#282c34",
        "sideBar.background": "#282c34",
        "activityBar.background": "#282c34"

    }
}
````
## USER SNIPPETS

### Snippets js
````js
{
	"Print to console": {
		"prefix": "clog",
		"body": [
			"console.log('');"
		],
		"description": "Log output to console"
	}
}
````
### Snippets CSS
````css
{
	"Adicionar Media Query": {
		"prefix": "@media",
		"body": [
			"@media screen and (min-width: 48rem) {}"
		],
		"description": "Media Queries"
	}
}
````

## Editor Config
````conf
[*]
indent_style = tab
end_of_line = lf
indent_size = 2
charset = utf-8
trim_trailing_whitespace = true
insert_final_newline = true
````

## Workspace Settings
````json
{
  "files.exclude": {
    "**/.git": true,
    "**/.gitignore": true,
    "**/.vscode": true,
    "**/.svn": true,
    "**/.hg": true,
    "**/CVS": true,
    "**/.DS_Store": true,
    "**/*js.map": true,
    "node_modules/**/*": true
  }
}
````

