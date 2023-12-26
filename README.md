# configVsCode

##Shortcuts

```
[
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
        "key": "ctrl+shift+alt+down",
        "command": "-editor.action.copyLinesDownAction",
        "when": "editorTextFocus && !editorReadonly"
    },
    {
        "key": "shift+alt+up",
        "command": "-notebook.cell.copyUp",
        "when": "notebookEditorFocused && !inputFocus"
    },
    {
        "key": "shift+alt+up",
        "command": "editor.action.copyLinesUpAction",
        "when": "editorTextFocus && !editorReadonly"
    },
    {
        "key": "ctrl+shift+alt+up",
        "command": "-editor.action.copyLinesUpAction",
        "when": "editorTextFocus && !editorReadonly"
    },
    {
        "key": "ctrl+shift+s",
        "command": "-workbench.action.files.saveAs"
    },
    {
        "key": "ctrl+shift+s",
        "command": "-workbench.action.files.saveLocalFile",
        "when": "remoteFileDialogVisible"
    },
    {
        "key": "ctrl+shift+s",
        "command": "workbench.action.files.saveFiles"
	},
	{
		"key": "ctrl+shift+j",
		"command": "editor.action.joinLines"
	},
	{
		"key": "shift+alt+f shift+alt+e",
		"command": "editor.emmet.action.splitJoinTag"
	},
	{
		"key": "ctrl+shift+e",
		"command": "-workbench.action.quickOpenNavigatePreviousInFilePicker",
		"when": "inFilesPicker && inQuickOpen"
	},
	{
		"key": "ctrl+alt+3",
		"command": "editor.action.commentLine",
		"when": "editorTextFocus && !editorReadonly"
	},
	{
		"key": "ctrl+shift+n",
		"command": "explorer.newFolder",
		"when": "filesExplorerFocus"
	},
	{
		"key": "ctrl+n",
		"command": "explorer.newFile",
		"when": "filesExplorerFocus"
	},
	{
		"key": "shift+alt+c shift+alt+d",
		"command": "editor.emmet.action.wrapWithAbbreviation",
		"when": "editorFocus"
	},
	{
		"key": "ctrl+alt+f",
		"command": "editor.action.toggleColumnSelection"
	},
	{
		"key": "end",
		"command": "cursorEnd",
		"when": "textInputFocus"
	},
	{
		"key": "end",
		"command": "-cursorEnd",
		"when": "textInputFocus"
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
		"key": "ctrl+alt+l",
		"command": "cursorRight",
		"when": "textInputFocus"
	},
	{
		"key": "shift+alt+c shift+alt+s",
		"command": "turboConsoleLog.displayLogMessage"
	},
	{
		"key": "ctrl+alt+l",
		"command": "-turboConsoleLog.displayLogMessage"
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
		"key": "ctrl+shift+alt+j",
		"command": "cursorWordLeftSelect",
		"when": "textInputFocus"
	},
	{
		"key": "ctrl+shift+alt+i",
		"command": "cursorUpSelect",
		"when": "textInputFocus"
	},
	{
		"key": "ctrl+shift+alt+k",
		"command": "cursorDownSelect",
		"when": "textInputFocus"
	},
	{
		"key": "ctrl+shift+alt+l",
		"command": "cursorWordEndRightSelect",
		"when": "textInputFocus"
	},
	{
		"key": "ctrl+alt+e",
		"command": "editor.action.deleteLines",
		"when": "textInputFocus && !editorReadonly"
	},
	{
		"key": "ctrl+shift+k",
		"command": "-editor.action.deleteLines",
		"when": "textInputFocus && !editorReadonly"
	},
	{
		"key": "ctrl+shift+k",
		"command": "editor.action.insertCursorBelow",
		"when": "editorTextFocus"
	},
	{
		"key": "ctrl+shift+i",
		"command": "-notebook.formatCell",
		"when": "editorHasDocumentFormattingProvider && editorTextFocus && inCompositeEditor && notebookEditable && !editorReadonly && activeEditor == 'workbench.editor.notebook'"
	},
	{
		"key": "ctrl+shift+i",
		"command": "-editor.action.formatDocument",
		"when": "editorHasDocumentFormattingProvider && editorTextFocus && !editorReadonly && !inCompositeEditor"
	},
	{
		"key": "ctrl+shift+i",
		"command": "-editor.action.formatDocument.none",
		"when": "editorTextFocus && !editorHasDocumentFormattingProvider && !editorReadonly"
	},
	{
		"key": "ctrl+shift+i",
		"command": "-notebook.format",
		"when": "notebookEditable && !editorTextFocus && activeEditor == 'workbench.editor.notebook'"
	},
	{
		"key": "ctrl+shift+i",
		"command": "editor.action.insertCursorAbove",
		"when": "editorTextFocus"
	},
	{
		"key": "shift+alt+c shift+alt+h",
		"command": "git.checkout"
	},
	{
		"key": "ctrl+alt+i",
		"command": "cursorUp",
		"when": "textInputFocus"
	},
	{
		"key": "ctrl+alt+k",
		"command": "cursorDown",
		"when": "textInputFocus"
	},
	{
		"key": "ctrl+alt+j",
		"command": "cursorLeft",
		"when": "textInputFocus"
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
		"key": "ctrl+j",
		"command": "cursorWordLeft",
		"when": "editorColumnSelection && textInputFocus"
	},
	{
		"key": "ctrl+l",
		"command": "cursorWordEndRight",
		"when": "editorColumnSelection && textInputFocus"
	},
	{
		"key": "ctrl+shift+j",
		"command": "cursorWordLeftSelect",
		"when": "editorColumnSelection && textInputFocus"
	},
	{
		"key": "ctrl+shift+l",
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
		"key": "ctrl+shift+alt+l",
		"command": "editor.action.smartSelect.expand",
		"when": "editorColumnSelection && textInputFocus"
	},
	{
		"key": "ctrl+alt+1",
		"command": "editor.fold",
		"when": "editorTextFocus && foldingEnabled"
	},
	{
		"key": "ctrl+alt+2",
		"command": "editor.unfold",
		"when": "editorTextFocus && foldingEnabled"
	},
	{
		"key": "ctrl+shift+q",
		"command": "workbench.action.quit"
	},
	{
		"key": "ctrl+q",
		"command": "-workbench.action.quit"
	},
	{
		"key": "ctrl+shift+r",
		"command": "-workbench.view.extension.rapidapi-explorer"
	},
	{
		"key": "shift+alt+c shift+alt+o",
		"command": "extension.conventionalCommits"
	},
	{
		"key": "ctrl+alt+c ctrl+alt+1",
		"command": "workbench.files.action.collapseExplorerFolders"
	},
	{
		"key": "ctrl+shift+alt+e",
		"command": "outline.focus"
	},
	{
		"key": "ctrl+shift+y",
		"command": "redo"
	},
	{
		"key": "ctrl+y",
		"command": "-redo"
	},
	{
		"key": "ctrl+shift+space",
		"command": "editor.action.quickFix",
		"when": "editorHasCodeActionsProvider && textInputFocus && !editorReadonly"
	},
	{
		"key": "ctrl+shift+l",
		"command": "-RCC:create-component"
	},
	{
		"key": "ctrl+enter",
		"command": "-github.copilot.generate",
		"when": "editorTextFocus && github.copilot.activated && !inInteractiveInput && !interactiveEditorFocused"
	},
	{
		"key": "ctrl+shift+g c",
		"command": "-gitlens.showQuickCommitFileDetails",
		"when": "editorTextFocus && !gitlens:disabled && config.gitlens.keymap == 'chorded'"
	},
	{
		"key": "ctrl+shift+g c",
		"command": "workbench.panel.chat.view.copilot.focus"
	},
	{
		"key": "shift+alt+h shift+alt+i",
		"command": "workbench.action.activityBarLocation.hide"
	},
	{
		"key": "ctrl+shift+alt+h ctrl+shift+alt+i",
		"command": "workbench.action.activityBarLocation.side"
	}
]
```

##Snippets vue & js

```
{
	// HTML //
	"Base3Setup": {
		"prefix": "b3s",
		"body": [
			"<template>",
				"\t${1:<div>${2:<h1>${3:Hello Page}</h1>}</div>}",
			"</template>",
			"",
			"<script setup>",
			"import { ref } from 'vue';",
			"",
			"</script>",
			"",
			"<style lang=\"scss\" scoped>",
			"</style>"
		],
		"description": "Agrega un modal de element con estructura de yap"
	},
	"Base3Component": {
		"prefix": "b3component",
		"body": [
			"<script setup>",
			"import { ref } from 'vue';",
			"",
			"const props = defineProps({",
				"\ttitle: {",
				"\t\ttype: String,",
				"\t\tdefault: ''",
				"\t}",
			"})",
			"</script>",
			"",
			"<template>",
				"\t$1",
			"</template>",
			"",
			"<style lang=\"scss\" scoped>",
			"</style>"
		],
		"description": "Agrega template de vue 3 para componentes"
	},
	"FooterModalFalse": {
		"prefix": "footermodal",
		"body": [
			":btnCancel=\"false\" :btnConfirm=\"false\""
		],
		"description": "Añade las propiedades para que el modal no tenga un footer"
	},
	"FooterModalFalse": {
		"prefix": "styl",
		"body": [
			"style=\"$1\""
		],
		"description": "Inserta un style de linea html"
	},

	// Vue //
	"Vue3Props": {
		"prefix": "v3props",
		"body": [
			"const props = defineProps({",
				"\t${1:title}: {",
				"\t\ttype: ${2:String},",
				"\t\tdefault: '$3'",
				"\t}",
			"})"
		],
		"description": "Vue3Props"
	},
	"v-for-index": {
		"prefix": "vfi",
		"body": [
			"v-for=\"(${1:data}, ${2:index}) in ${3:4}\" :key=\"${2:index}\""
		],
		"description": "v-for de vue"
	},
	"v-for": {
		"prefix": "vf",
		"body": [
			"v-for=\"${1:data} in ${2:4}\" :key=\"${3:index}\""
		],
		"description": "v-for de vue"
	},
	"el-select": {
		"prefix": "elselect",
		"body": [
			"<el-select v-model=\"$1\" placeholder=\"$2\">",
				"\t<el-option $5 :label=\"$3\" :value=\"$4\" />",
			"</el-select>"
		],
		"description": "v-for de vue"
	},

	// Scrips //
	"ConsoleLog": {
		"prefix": "csl",
		"body": [
			"console.log(\"${1:DATA }\", $2)"
		],
		"description": "Console.log()"
	},
	"function": {
		"prefix": "funccccccc",
		"body": [
			"function ${1:name}(${2:params}) {",
			"\t$3",
			"};"
		],
		"description": "Function JS"
	},
	"arrayFunction": {
		"prefix": "arf",
		"body": [
			"() => $1"
		],
		"description": "Array Function JS"
	},
	"IfLine": {
		"prefix": "ifline",
		"body": [
			"if ($1) $2"
		],
		"description": "If Line"
	},
	"IfElseLine": {
		"prefix": "ifeline",
		"body": [
			"if($1) $2",
			"else $3"
		],
		"description": "If Else Line"
	},
	"IfReturn": {
		"prefix": "ifreturn",
		"body": [
			"if($1) return"
		],
		"description": "If Return"
	},

	// Class styles //
	"CursorDefaultP": {
		"prefix": "pcd",
		"body": [
			"p{",
				"\tuser-select: none;",
				"\t&:not(.cr-pointer){",
				"\t\tcursor: default;",
				"\t}",
			"}"
		],
		"description": "Cambia estilos del cursor a default en las etiquetas P"
	},
	"widthMinMaxDinamic": {
		"prefix": "wdinamic",
		"body": [
			"width: min(100% - 80px, 500px);"
		],
		"description": "Asigna un width dinamico entre un min y un max"
	},
}
```
