# `index.test.ts`

**DO NOT MODIFY**. This file has been autogenerated. Run `rome test internal/js-parser/index.test.ts --update-snapshots` to update.

## `experimental > export-extensions > default-default-asi`

### `ast`

```javascript
JSRoot {
	comments: Array []
	corrupt: false
	diagnostics: Array []
	directives: Array []
	filename: "experimental/export-extensions/default-default-asi/input.js"
	hasHoistedVars: false
	interpreter: undefined
	mtime: undefined
	sourceType: "module"
	syntax: Array []
	loc: Object {
		filename: "experimental/export-extensions/default-default-asi/input.js"
		end: Object {
			column: 0
			line: 3
		}
		start: Object {
			column: 0
			line: 1
		}
	}
	body: Array [
		JSExportDefaultDeclaration {
			loc: Object {
				filename: "experimental/export-extensions/default-default-asi/input.js"
				end: Object {
					column: 19
					line: 1
				}
				start: Object {
					column: 0
					line: 1
				}
			}
			declaration: JSReferenceIdentifier {
				name: "from"
				loc: Object {
					filename: "experimental/export-extensions/default-default-asi/input.js"
					identifierName: "from"
					end: Object {
						column: 19
						line: 1
					}
					start: Object {
						column: 15
						line: 1
					}
				}
			}
		}
		JSExpressionStatement {
			loc: Object {
				filename: "experimental/export-extensions/default-default-asi/input.js"
				end: Object {
					column: 6
					line: 2
				}
				start: Object {
					column: 0
					line: 2
				}
			}
			expression: JSStringLiteral {
				value: "bar"
				loc: Object {
					filename: "experimental/export-extensions/default-default-asi/input.js"
					end: Object {
						column: 5
						line: 2
					}
					start: Object {
						column: 0
						line: 2
					}
				}
			}
		}
	]
}
```

### `diagnostics`

```
✔ No known problems!

```
