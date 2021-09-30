---
title: VS Code settings
description: A starter settings file
---

# {{ page.title }}

```json
{
    "beautify.config": {
        "indent_size": "4",
        "indent_char": " ",
        "max_preserve_newlines": "5",
        "preserve_newlines": true,
        "keep_array_indentation": true,
        "break_chained_methods": false,
        "indent_scripts": "keep",
        "brace_style": "collapse",
        "space_before_conditional": true,
        "unescape_strings": false,
        "jslint_happy": false,
        "end_with_newline": true,
        "wrap_line_length": "0",
        "indent_inner_html": true,
        "comma_first": false,
        "indent_empty_lines": false
    },
    "beautify.language": {
        "html": ["html", "php", "erb", "liquid"],
        "css": [],
        "js": []
    },
    "prettier.trailingComma": "es5",
    "prettier.tabWidth": 4,
    "prettier.useTabs": false,
    "prettier.semi": true,
    "prettier.singleQuote": false,
    "prettier.printWidth": 1000,
    "html.format.indentHandlebars": true,
    "html.format.indentInnerHtml": true,
    "html.format.wrapAttributes": "preserve",
    "files.insertFinalNewline": true
}
```
