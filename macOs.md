
## Shortcuts

```Javascript
// Place your key bindings in this file to override the defaults
[
	{
		"key": "cmd+r",
		"command": "workbench.action.openRecent"
	},
	{
		"key": "cmd+`",
		"command": "workbench.action.terminal.toggleTerminal",
		"when": "terminal.active"
	},


	//Personalizados de Eimer
	// DE MOVIMIENTO:
	{
		"key": "cmd+alt+l",
		"command": "cursorRight",
		"when": "textInputFocus"
	},
{
		"key": "cmd+alt+i",
		"command": "cursorUp",
		"when": "textInputFocus"
	},
	{
		"key": "cmd+alt+k",
		"command": "cursorDown",
		"when": "textInputFocus"
	},
	{
		"key": "cmd+alt+j",
		"command": "cursorLeft",
		"when": "textInputFocus"
	},
	// movimiento en tree
	{
		"key": "alt+cmd+k",
		"command": "list.focusDown",
		"when": "listFocus && !inputFocus && !treestickyScrollFocused"
	},
	{
		"key": "alt+cmd+i",
		"command": "list.focusUp",
		"when": "listFocus && !inputFocus && !treestickyScrollFocused"
	},
	{
		"key": "alt+cmd+l",
		"command": "list.expand",
		"when": "listFocus && treeElementCanExpand && !inputFocus && !treestickyScrollFocused || listFocus && treeElementHasChild && !inputFocus && !treestickyScrollFocused"
	},
	{
		"key": "alt+cmd+j",
		"command": "list.collapse",
		"when": "listFocus && treeElementCanCollapse && !inputFocus && !treestickyScrollFocused || listFocus && treeElementHasParent && !inputFocus && !treestickyScrollFocused"
	},
	// movimiento con selección
	{
		"key": "cmd+shift+alt+j",
		"command": "cursorWordLeftSelect",
		"when": "textInputFocus"
	},
	{
		"key": "cmd+shift+alt+i",
		"command": "cursorUpSelect",
		"when": "textInputFocus"
	},
	{
		"key": "cmd+shift+alt+k",
		"command": "cursorDownSelect",
		"when": "textInputFocus"
	},
	{
		"key": "cmd+shift+alt+l",
		"command": "cursorWordEndRightSelect",
		"when": "textInputFocus"
	},
	// ========================================
	{
		"key": "cmd+alt+3",
		"command": "editor.action.commentLine",
		"when": "editorTextFocus && !editorReadonly"
	},
{
		"key": "cmd+alt+e",
		"command": "editor.action.deleteLines",
		"when": "textInputFocus && !editorReadonly"
	},
{
		"key": "cmd+alt+1",
		"command": "editor.fold",
		"when": "editorTextFocus && foldingEnabled"
	},
	{
		"key": "cmd+alt+2",
		"command": "editor.unfold",
		"when": "editorTextFocus && foldingEnabled"
	},
	{
		"key": "cmd+shift+s",
		"command": "workbench.action.files.saveFiles"
	},
	{
		"key": "cmd+shift+j",
		"command": "editor.action.joinLines"
	},
	// COMBOS
	{
		"key": "alt+cmd+c alt+cmd+h",
		"command": "git.checkout"
	},
	{
		"key": "alt+cmd+c alt+cmd+o",
		"command": "extension.conventionalCommits"
	},
	{
		"key": "cmd+alt+c cmd+alt+1",
		"command": "workbench.files.action.collapseExplorerFolders"
	},
	{
		"key": "shift+alt+f shift+alt+e",
		"command": "editor.emmet.action.splitJoinTag"
	},
	{
		"key": "shift+alt+c shift+alt+d",
		"command": "editor.emmet.action.wrapWithAbbreviation",
		"when": "editorFocus"
	},
	{
		"key": "shift+alt+c shift+alt+h",
		"command": "git.checkout"
	},
	{
		"key": "shift+alt+c shift+alt+o",
		"command": "extension.conventionalCommits"
	},
	{
		"key": "shift+alt+h shift+alt+i",
		"command": "workbench.action.activityBarLocation.hide"
	},
	// ========================================
	{
		"key": "cmd+shift+n",
		"command": "explorer.newFolder",
		"when": "filesExplorerFocus"
	},
	{
		"key": "cmd+n",
		"command": "explorer.newFile",
		"when": "filesExplorerFocus"
	},
	{
		"key": "alt+cmd+u",
		"command": "editor.action.toggleColumnSelection"
	},
	{
		"key": "shift+alt+l",
		"command": "cursorEnd",
		"when": "textInputFocus"
	},
	{
		"key": "shift+alt+down",
		"command": "editor.action.copyLinesDownAction",
		"when": "editorTextFocus && !editorReadonly"
	},
	{
		"key": "shift+alt+j",
		"command": "cursorHome",
		"when": "textInputFocus"
	},
	{
		"key": "shift+alt+s shift+alt+j",
		"command": "cursorHomeSelect",
		"when": "textInputFocus"
	},
	{
		"key": "shift+alt+s shift+alt+l",
		"command": "cursorEndSelect",
		"when": "textInputFocus"
	},
	{
		"key": "shift+alt+k",
		"command": "editor.action.copyLinesDownAction",
		"when": "editorTextFocus && !editorReadonly"
	},
	{
		"key": "shift+alt+i",
		"command": "editor.action.copyLinesUpAction",
		"when": "editorTextFocus && !editorReadonly"
	},
	{
		"key": "cmd+shift+k",
		"command": "editor.action.insertCursorBelow",
		"when": "editorTextFocus"
	},
	{
		"key": "cmd+shift+i",
		"command": "editor.action.insertCursorAbove",
		"when": "editorTextFocus"
	},
	{
		"key": "i",
		"command": "cursorUp",
		"when": "editorColumnSelection && textInputFocus"
	},
	{
		"key": "k",
		"command": "cursorDown",
		"when": "editorColumnSelection && textInputFocus"
	},
	{
		"key": "j",
		"command": "cursorLeft",
		"when": "editorColumnSelection && textInputFocus"
	},
	{
		"key": "l",
		"command": "cursorRight",
		"when": "editorColumnSelection && textInputFocus"
	},
	{
		"key": "shift+i",
		"command": "cursorUpSelect",
		"when": "editorColumnSelection && textInputFocus"
	},
	{
		"key": "shift+k",
		"command": "cursorDownSelect",
		"when": "editorColumnSelection && textInputFocus"
	},
	{
		"key": "shift+j",
		"command": "cursorLeftSelect",
		"when": "editorColumnSelection && textInputFocus"
	},
	{
		"key": "shift+l",
		"command": "cursorRightSelect",
		"when": "editorColumnSelection && textInputFocus"
	},
	{
		"key": "cmd+j",
		"command": "cursorWordLeft",
		"when": "editorColumnSelection && textInputFocus"
	},
	{
		"key": "cmd+l",
		"command": "cursorWordEndRight",
		"when": "editorColumnSelection && textInputFocus"
	},
	{
		"key": "cmd+shift+j",
		"command": "cursorWordLeftSelect",
		"when": "editorColumnSelection && textInputFocus"
	},
	{
		"key": "cmd+shift+l",
		"command": "cursorWordEndRightSelect",
		"when": "editorColumnSelection && textInputFocus"
	},
	{
		"key": "alt+i",
		"command": "editor.action.moveLinesUpAction",
		"when": "editorColumnSelection && textInputFocus && !editorReadonly"
	},
	{
		"key": "alt+k",
		"command": "editor.action.moveLinesDownAction",
		"when": "editorColumnSelection && textInputFocus && !editorReadonly"
	},
	{
		"key": "cmd+shift+alt+l",
		"command": "editor.action.smartSelect.expand",
		"when": "editorColumnSelection && textInputFocus"
	},
	{
		"key": "cmd+shift+alt+e",
		"command": "outline.focus"
	},
	{
		"key": "alt+cmd+n",
		"command": "turboConsoleLog.displayLogMessage"
	},
	{
		"key": "shift+cmd+g",
		"command": "workbench.view.scm",
		"when": "workbench.scm.active"
	},
	{
		"key": "ctrl+w",
		"command": "toggleSearchEditorWholeWord",
		"when": "inSearchEditor && searchInputBoxFocus"
	},
	{
		"key": "cmd+backspace",
		"command": "deleteWordLeft",
		"when": "textInputFocus && !editorReadonly"
	},
	{
		"key": "cmd+f",
		"command": "actions.findWithSelection"
	},
	{
		"key": "shift+alt+right",
		"command": "editor.action.smartSelect.expand",
		"when": "editorTextFocus"
	},
	{
		"key": "alt+f4",
		"command": "workbench.action.closeWindow"
	},
	{
		"key": "cmd+y",
		"command": "redo"
	},
	{
		"key": "cmd+space",
		"command": "focusSuggestion",
		"when": "suggestWidgetVisible && textInputFocus && !suggestWidgetHasFocusedSuggestion"
	},
	{
		"key": "cmd+space",
		"command": "toggleSuggestionDetails",
		"when": "suggestWidgetHasFocusedSuggestion && suggestWidgetVisible && textInputFocus"
	},
	{
		"key": "cmd+space",
		"command": "workbench.action.terminal.sendSequence",
		"when": "terminalFocus && terminalShellIntegrationEnabled && !accessibilityModeEnabled && terminalShellType == 'pwsh'"
	},
	{
		"key": "cmd+space",
		"command": "workbench.action.terminal.sendSequence",
		"when": "config.terminal.integrated.suggest.enabled && terminalFocus && terminalShellIntegrationEnabled && !accessibilityModeEnabled && terminalShellType == 'pwsh'"
	},


	// Eliminados
	{
		"key": "cmd+r",
		"command": "-workbench.action.reloadWindow",
		"when": "isDevelopment"
	},
	{
		"key": "cmd+r",
		"command": "-python.refreshTensorBoard",
		"when": "python.hasActiveTensorBoardSession"
	},
	{
		"key": "cmd+r",
		"command": "-workbench.action.terminal.runRecentCommand",
		"when": "accessibilityModeEnabled && terminalFocus && terminalHasBeenCreated || accessibilityModeEnabled && terminalFocus && terminalProcessSupported || accessibilityModeEnabled && accessibleViewIsShown && terminalHasBeenCreated && accessibleViewCurrentProviderId == 'terminal' || accessibilityModeEnabled && accessibleViewIsShown && terminalProcessSupported && accessibleViewCurrentProviderId == 'terminal'"
	},
	{
		"key": "ctrl+r",
		"command": "-workbench.action.openRecent"
	},
	{
		"key": "ctrl+`",
		"command": "-workbench.action.terminal.toggleTerminal",
		"when": "terminal.active"
	},
	{
		"key": "alt+cmd+i",
		"command": "-workbench.action.toggleDevTools",
		"when": "isDevelopment"
	},
	{
		"key": "alt+cmd+l",
		"command": "-toggleSearchEditorContextLines",
		"when": "inSearchEditor"
	},
	{
		"key": "alt+cmd+l",
		"command": "-toggleFindInSelection",
		"when": "editorFocus"
	},
	{
		"key": "alt+cmd+k",
		"command": "-keybindings.editor.recordSearchKeys",
		"when": "inKeybindings && inKeybindingsSearch"
	},
	{
		"key": "shift+alt+up",
		"command": "-editor.action.insertCursorAbove",
		"when": "editorTextFocus"
	},
	{
		"key": "shift+alt+down",
		"command": "-editor.action.insertCursorBelow",
		"when": "editorTextFocus"
	},
	{
		"key": "shift+alt+down",
		"command": "-notebook.cell.copyDown",
		"when": "notebookEditorFocused && !inputFocus"
	},
	{
		"key": "cmd+shift+alt+down",
		"command": "-editor.action.copyLinesDownAction",
		"when": "editorTextFocus && !editorReadonly"
	},
	{
		"key": "cmd+shift+alt+up",
		"command": "-editor.action.copyLinesUpAction",
		"when": "editorTextFocus && !editorReadonly"
	},
	{
		"key": "cmd+shift+e",
		"command": "-workbench.action.quickOpenNavigatePreviousInFilePicker",
		"when": "inFilesPicker && inQuickOpen"
	},
	{
		"key": "shift+cmd+g",
		"command": "-editor.action.previousMatchFindAction",
		"when": "editorFocus"
	},
	{
		"key": "shift+cmd+g",
		"command": "-workbench.action.terminal.findPrevious",
		"when": "terminalFindFocused && terminalHasBeenCreated || terminalFindFocused && terminalProcessSupported || terminalFocusInAny && terminalHasBeenCreated || terminalFocusInAny && terminalProcessSupported"
	},
	{
		"key": "shift+cmd+g",
		"command": "-workbench.action.terminal.openDetectedLink",
		"when": "accessibleViewIsShown && terminalHasBeenCreated && accessibleViewCurrentProviderId == 'terminal'"
	},
	{
		"key": "ctrl+shift+g",
		"command": "-workbench.view.scm",
		"when": "workbench.scm.active"
	},
	{
		"key": "alt+c",
		"command": "-gitlens.showQuickCommitFileDetails",
		"when": "editorTextFocus && !gitlens:disabled && config.gitlens.keymap == 'alternate'"
	},
	{
		"key": "alt+cmd+w",
		"command": "-toggleSearchEditorWholeWord",
		"when": "inSearchEditor && searchInputBoxFocus"
	},
	{
		"key": "alt+cmd+w",
		"command": "-workbench.action.terminal.toggleFindWholeWord",
		"when": "terminalFindVisible && terminalHasBeenCreated || terminalFindVisible && terminalProcessSupported"
	},
	{
		"key": "alt+cmd+w",
		"command": "-toggleFindWholeWord",
		"when": "editorFocus"
	},
	{
		"key": "alt+cmd+w",
		"command": "-toggleSearchWholeWord",
		"when": "searchViewletFocus"
	},
	{
		"key": "cmd+backspace",
		"command": "-deleteAllLeft",
		"when": "textInputFocus && !editorReadonly"
	},
	{
		"key": "alt+backspace",
		"command": "-deleteWordLeft",
		"when": "textInputFocus && !editorReadonly"
	},
	{
		"key": "cmd+e",
		"command": "-actions.findWithSelection"
	},
	{
		"key": "shift+alt+right",
		"command": "-cursorWordEndRightSelect",
		"when": "textInputFocus"
	},
	{
		"key": "ctrl+shift+cmd+right",
		"command": "-editor.action.smartSelect.expand",
		"when": "editorTextFocus"
	},
	{
		"key": "ctrl+shift+right",
		"command": "-editor.action.smartSelect.expand",
		"when": "editorTextFocus"
	},
	{
		"key": "shift+cmd+y",
		"command": "-workbench.debug.action.toggleRepl",
		"when": "workbench.panel.repl.view.active"
	},
	{
		"key": "cmd+q",
		"command": "-workbench.action.quit"
	},
	{
		"key": "ctrl+space",
		"command": "-focusSuggestion",
		"when": "suggestWidgetVisible && textInputFocus && !suggestWidgetHasFocusedSuggestion"
	},
	{
		"key": "ctrl+space",
		"command": "-toggleSuggestionDetails",
		"when": "suggestWidgetHasFocusedSuggestion && suggestWidgetVisible && textInputFocus"
	},
	{
		"key": "ctrl+space",
		"command": "-workbench.action.terminal.sendSequence",
		"when": "terminalFocus && terminalShellIntegrationEnabled && !accessibilityModeEnabled && terminalShellType == 'pwsh'"
	},
	{
		"key": "ctrl+space",
		"command": "-workbench.action.terminal.sendSequence",
		"when": "config.terminal.integrated.suggest.enabled && terminalFocus && terminalShellIntegrationEnabled && !accessibilityModeEnabled && terminalShellType == 'pwsh'"
	},
	{
		"key": "cmd+p",
		"command": "-workbench.action.quickOpenNavigateNextInFilePicker",
		"when": "inFilesPicker && inQuickOpen"
	},
	{
		"key": "alt+a",
		"command": "-codeium.diffActionAccept",
		"when": "editorTextFocus && !inlineSuggestionsVisible"
	},
	{
		"key": "alt+f",
		"command": "-codeium.diffActionFollowup",
		"when": "editorTextFocus && !inlineSuggestionsVisible"
	},
	{
		"key": "alt+r",
		"command": "-codeium.diffActionReject",
		"when": "editorTextFocus && !inlineSuggestionsVisible"
	},
	{
		"key": "shift+cmd+space",
		"command": "-editor.action.triggerParameterHints",
		"when": "editorHasSignatureHelpProvider && editorTextFocus"
	},
	{
		"key": "cmd+space",
		"command": "editor.action.inlineEdits.accept",
		"when": "inlineEditsVisible"
	},
	{
		"key": "cmd+space",
		"command": "-editor.action.inlineEdits.accept",
		"when": "inlineEditsVisible"
	},
	{
		"key": "cmd+space",
		"command": "editor.action.triggerSuggest",
		"when": "editorHasCompletionItemProvider && textInputFocus && !editorReadonly && !suggestWidgetVisible"
	},
	{
		"key": "ctrl+space",
		"command": "-editor.action.triggerSuggest",
		"when": "editorHasCompletionItemProvider && textInputFocus && !editorReadonly && !suggestWidgetVisible"
	},
]
```

## Config

```Javascript
{
	"workbench.colorCustomizations": {
		"[One Dark Pro Darker]": {
			"editor.background": "#060b1a",
			"sideBar.background": "#121624",
			"sideBarSectionHeader.background": "#060b1a",
			"activityBar.background": "#060b1a",
			"statusBar.background": "#060b1a",
			"titleBar.activeBackground": "#060b1a",
			"editorGroupHeader.tabsBackground": "#060b1a",
			"tab.inactiveBackground": "#121624",
			"tab.activeBackground": "#060b1a",
			"terminal.background": "#060b1a"
		},
		"[Dracula Theme]": {
			"editor.background": "#060b1a",
			"sideBar.background": "#080d1e",
			"sideBarSectionHeader.background": "#060b1a",
			"activityBar.background": "#060b1a",
			"activityBar.inactiveForeground": "#ffffff",
			// "statusBar.background": "#060b1a",
			"titleBar.activeBackground": "#060b1a",
			"editorGroupHeader.tabsBackground": "#060b1a",
			"tab.inactiveBackground": "#060b1a",
			"tab.activeBackground": "#1a2033",
			"tab.activeBorder": "#BD93F9",
			"tab.activeBorderTop": "#0fb100",
			"tab.activeForeground": "#ffffff",
			"terminal.background": "#060b1a"
		}
	},
	"editor.tokenColorCustomizations": {
		"[*Light*]": {
			"textMateRules": [
				{
					"scope": "ref.matchtext",
					"settings": {
						"foreground": "#000"
					}
				}
			]
		},
		"[*Dark*]": {
			"textMateRules": [
				{
					"scope": "ref.matchtext",
					"settings": {
						"foreground": "#fff"
					}
				}
			]
		},
		"[Dracula Theme]": {
			"variables": "#d5cdf8",
			"strings": "#3be766",
			"textMateRules": [
				{
					"scope": [
						"punctuation.definition.string.begin",
						"punctuation.definition.string.end"
					],
					"settings": {
						"foreground": "#3be766",
						"fontStyle": "bold"
					}
				},
				{
					"scope": [
						"entity.name.function"
					],
					"settings": {
						"fontStyle": "italic bold"
					}
				},
				{
					"scope": [
						"variable.other.object.js"
					],
					"settings": {
						"foreground": "#BD93F9",
						"fontStyle": "italic"
					}
				},
				{
					"scope": [
						"entity.name.tag"
					],
					"settings": {
						"fontStyle": "italic"
					}
				},
				{
					"scope": [
						"entity.other.attribute-name"
					],
					"settings": {
						"foreground": "#FFB86C",
						"fontStyle": "italic"
					}
				}
			]
		},
		"[One Dark Pro Darker]": {
			"strings": "#0bd65f",
			"functions": "#41c1f8",
			"variables": "#eaeaea",
			"textMateRules": [
				{
					"scope": [
						"entity.name.tag.block.any.html",
						"meta.tag.block.any.html",
						"text.html.vue-html",
						"source.vue",
						"entity.name.tag"
					],
					"settings": {
						"foreground": "#37aee0",
						"fontStyle": "bold"
					}
				},
				{
					"scope": [
						"variable.language.this.js",
						"meta.block.js",
						"meta.method.declaration.js",
						"meta.objectliteral.js",
						"meta.object.member.js",
						"meta.objectliteral.js",
						"meta.export.default.js",
						"source.js",
						"source.vue"
					],
					"settings": {
						"foreground": "#ec7c4c",
						"fontStyle": "italic bold"
					}
				},
				{
					"scope": [
						"variable.other.object.property.js",
						"meta.function-call.js",
						"meta.block.js",
						"meta.method.declaration.js",
						"meta.objectliteral.js",
						"meta.object.member.js",
						"meta.objectliteral.js",
						"meta.export.default.js",
						"source.js",
						"source.vue"
					],
					"settings": {
						"foreground": "#e6e6e6",
						"fontStyle": "italic"
					}
				}
			]
		},
		"textMateRules": []
	},
	"editor.semanticTokenColorCustomizations": {
		"enabled": true,
		"[One Dark Pro Darker]": {
			"rules": {
				"method": "#41c1f8",
				"property": "#e6e6e6"
			}
		}
	},
	"peacock.favoriteColors": [
		{
			"name": "Angular Red",
			"value": "#dd0531"
		},
		{
			"name": "Azure Blue",
			"value": "#007fff"
		},
		{
			"name": "JavaScript Yellow",
			"value": "#f9e64f"
		},
		{
			"name": "Mandalorian Blue",
			"value": "#1857a4"
		},
		{
			"name": "Node Green",
			"value": "#215732"
		},
		{
			"name": "React Blue",
			"value": "#61dafb"
		},
		{
			"name": "Something Different",
			"value": "#832561"
		},
		{
			"name": "Svelte Orange",
			"value": "#ff3d00"
		},
		{
			"name": "Vue Green",
			"value": "#42b883"
		}
	],
	"indentRainbow.colors": [
		"rgba(255,255,64,0.004)",
		"rgba(127,255,127,0.004)",
		"rgba(255,127,255,0.004)",
		"rgba(79,236,236,0.004)"
	],
	"background.fullscreen": {
		"images": [
		],
		"opacity": 0.9, // 0.85 ~ 0.95 recommended
		"size": "cover",
		"position": "center",
		"interval": 35 // seconds of interval for carousel, default `0` to disabled.
	},
	"vscode-blur-linux.opacity": 100,
	"editor.defaultFormatter": "dbaeumer.vscode-eslint",
	"editor.tabSize": 4,
	"editor.insertSpaces": false,
	"editor.suggestSelection": "first",
	"vsintellicode.modify.editor.suggestSelection": "automaticallyOverrodeDefaultValue",
	"workbench.colorTheme": "Dracula Theme",
	"security.workspace.trust.untrustedFiles": "open",
	"workbench.editor.wrapTabs": true,
	"editor.cursorBlinking": "expand",
	"editor.fontFamily": "'Cascadia Code PL', 'Droid Sans Mono', 'monospace', monospace",
	"editor.fontLigatures": true,
	"editor.fontSize": 15,
	"terminal.integrated.fontSize": 15,
	"workbench.productIconTheme": "bongocat",
	"editor.guides.bracketPairs": true,
	"symbols.hidesExplorerArrows": false,
	"oneDarkPro.bold": true,
	"oneDarkPro.vivid": true,
	"workbench.preferredDarkColorTheme": "Default High Contrast",
	"editor.cursorSurroundingLines": 4,
	"editor.cursorWidth": 5,
	"editor.cursorStyle": "block",
	"git.suggestSmartCommit": false,
	"editor.stickyScroll.enabled": true,
	"editor.bracketPairColorization.independentColorPoolPerBracketType": true,
	"vsicons.dontShowNewVersionMessage": true,
	"terminal.integrated.defaultProfile.windows": "Git Bash",
	"auto-close-tag.insertSpaceBeforeSelfClosingTag": true,
	"vue-helper.indent-size": 4,
	"workbench.startupEditor": "none",
	"security.workspace.trust.enabled": false,
	"workbench.editorAssociations": {
		"*.ipynb": "jupyter-notebook"
	},
	"editor.codeActionsOnSave": {
		"source.fixAll.eslint": "explicit"
	},
	"cSpell.userWords": [
		"clsx",
		"dayjs",
		"figma",
		"hookform",
		"keymap",
		"Pinia",
		"tailwindcss",
		"vstack"
	],
	"[html]": {
		"editor.defaultFormatter": "vscode.html-language-features"
	},
	"[jsonc]": {
		"editor.defaultFormatter": "vscode.json-language-features"
	},
	"[javascript]": {
		"editor.defaultFormatter": "vscode.typescript-language-features"
	},
	"[css]": {
		"editor.defaultFormatter": "vscode.css-language-features"
	},
	"[javascriptreact]": {
		"editor.defaultFormatter": "vscode.typescript-language-features"
	},
	"[php]": {
		"editor.defaultFormatter": "bmewburn.vscode-intelephense-client"
	},
	"[vue]": {
		"editor.defaultFormatter": "Vue.volar"
	},
	"[python]": {
		"editor.formatOnType": true
	},
	"[scss]": {
		"editor.defaultFormatter": "vscode.css-language-features"
	},
	"[json]": {
		"editor.defaultFormatter": "vscode.json-language-features"
	},
	"editor.minimap.showSlider": "always", //Barra de menus laterales git-search-docker
	"window.menuBarVisibility": "hidden", //Ocultar barra de menus Archivo, editar, vista, etc
	"editor.renderWhitespace": "all",
	"editor.accessibilitySupport": "on",
	"gitlens.advanced.messages": {
		"suppressCreatePullRequestPrompt": true
	},
	"workbench.sideBar.location": "right",
	"diffEditor.experimental.showMoves": true,
	"volar.format.initialIndent": {
		"html": false
	},
	"volar.autoCompleteRefs": true,
	"editor.stickyScroll.maxLineCount": 15,
	"workbench.tree.enableStickyScroll": true,
	"workbench.tree.stickyScrollMaxItemCount": 15,
	"[typescript]": {
		"editor.defaultFormatter": "vscode.typescript-language-features"
	},
	"[typescriptreact]": {
		"editor.defaultFormatter": "vscode.typescript-language-features"
	},
	"explorer.confirmDelete": false,
	"editor.linkedEditing": true,
	"security.promptForLocalFileProtocolHandling": false,
	"cSpell.language": "en,es-ES",
	"files.associations": {
		".env*": "dotenv",
		"*.svg": "html"
	},
	"dotenv.enableAutocloaking": false,
	"template-string-converter.validLanguages": [
		"svelte",
		"typescript",
		"javascript",
		"typescriptreact",
		"javascriptreact",
		"vue"
	],
	"css.lint.unknownAtRules": "ignore",
	"scss.lint.unknownAtRules": "ignore",
	"errorLens.exclude": [
		"Unknown word\\."
	],
	"window.customTitleBarVisibility": "auto",
	"workbench.activityBar.location": "bottom",
	"workbench.editor.customLabels.patterns": {
		"src/app/index.*": "/${dirname}.${extname}",
		"**/src/app/**/page.*": "||${dirname}.${extname}||"
	},
	"github.copilot.editor.enableAutoCompletions": true,
	"terminal.external.osxExec": "Warp.app",
	"window.commandCenter": false,
	"editor.accessibilitySupport": "off",
	"window.zoomLevel": -1,
	"scm.showHistoryGraph": false,
	"telemetry.telemetryLevel": "off",
	"diffEditor.maxComputationTime": 0,
	"workbench.iconTheme": "material-icon-theme",
	"github.copilot.enable": {
		"*": false,
		"plaintext": false,
		"markdown": false,
		"scminput": false
	}
}
```