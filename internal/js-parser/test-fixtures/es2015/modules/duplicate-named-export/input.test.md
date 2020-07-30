# `index.test.ts`

**DO NOT MODIFY**. This file has been autogenerated. Run `rome test internal/js-parser/index.test.ts --update-snapshots` to update.

## `es2015 > modules > duplicate-named-export`

### `ast`

```javascript
JSRoot {
	comments: Array []
	corrupt: false
	directives: Array []
	filename: "es2015/modules/duplicate-named-export/input.js"
	hasHoistedVars: false
	interpreter: undefined
	mtime: undefined
	sourceType: "module"
	syntax: Array []
	loc: Object {
		filename: "es2015/modules/duplicate-named-export/input.js"
		end: Object {
			column: 0
			index: 39
			line: 3
		}
		start: Object {
			column: 0
			index: 0
			line: 1
		}
	}
	diagnostics: Array [
		Object {
			origins: Array [Object {category: "parse/js"}]
			location: Object {
				filename: "es2015/modules/duplicate-named-export/input.js"
				mtime: undefined
				sourceText: undefined
				end: Object {
					column: 19
					index: 35
					line: 2
				}
				start: Object {
					column: 9
					index: 25
					line: 2
				}
			}
			description: Object {
				category: "parse/js"
				message: MARKUP {
					parts: Array [
						RAW_MARKUP {value: "`"}
						"foo"
						RAW_MARKUP {value: "` has already been exported. Exported identifiers must be unique."}
					]
				}
				advice: Array [
					log {
						category: "info"
						text: MARKUP {parts: Array [RAW_MARKUP {value: "Defined already here"}]}
					}
					frame {
						location: Object {
							filename: "es2015/modules/duplicate-named-export/input.js"
							end: Object {
								column: 12
								index: 12
								line: 1
							}
							start: Object {
								column: 9
								index: 9
								line: 1
							}
						}
					}
				]
			}
		}
	]
	body: Array [
		JSExportLocalDeclaration {
			declaration: undefined
			exportKind: "value"
			loc: Object {
				filename: "es2015/modules/duplicate-named-export/input.js"
				end: Object {
					column: 15
					index: 15
					line: 1
				}
				start: Object {
					column: 0
					index: 0
					line: 1
				}
			}
			specifiers: Array [
				JSExportLocalSpecifier {
					loc: Object {
						filename: "es2015/modules/duplicate-named-export/input.js"
						end: Object {
							column: 12
							index: 12
							line: 1
						}
						start: Object {
							column: 9
							index: 9
							line: 1
						}
					}
					exported: JSIdentifier {
						name: "foo"
						loc: Object {
							filename: "es2015/modules/duplicate-named-export/input.js"
							identifierName: "foo"
							end: Object {
								column: 12
								index: 12
								line: 1
							}
							start: Object {
								column: 9
								index: 9
								line: 1
							}
						}
					}
					local: JSReferenceIdentifier {
						name: "foo"
						loc: Object {
							filename: "es2015/modules/duplicate-named-export/input.js"
							identifierName: "foo"
							end: Object {
								column: 12
								index: 12
								line: 1
							}
							start: Object {
								column: 9
								index: 9
								line: 1
							}
						}
					}
				}
			]
		}
		JSExportLocalDeclaration {
			declaration: undefined
			exportKind: "value"
			loc: Object {
				filename: "es2015/modules/duplicate-named-export/input.js"
				end: Object {
					column: 22
					index: 38
					line: 2
				}
				start: Object {
					column: 0
					index: 16
					line: 2
				}
			}
			specifiers: Array [
				JSExportLocalSpecifier {
					loc: Object {
						filename: "es2015/modules/duplicate-named-export/input.js"
						end: Object {
							column: 19
							index: 35
							line: 2
						}
						start: Object {
							column: 9
							index: 25
							line: 2
						}
					}
					exported: JSIdentifier {
						name: "foo"
						loc: Object {
							filename: "es2015/modules/duplicate-named-export/input.js"
							identifierName: "foo"
							end: Object {
								column: 19
								index: 35
								line: 2
							}
							start: Object {
								column: 16
								index: 32
								line: 2
							}
						}
					}
					local: JSReferenceIdentifier {
						name: "bar"
						loc: Object {
							filename: "es2015/modules/duplicate-named-export/input.js"
							identifierName: "bar"
							end: Object {
								column: 12
								index: 28
								line: 2
							}
							start: Object {
								column: 9
								index: 25
								line: 2
							}
						}
					}
				}
			]
		}
	]
}
```

### `diagnostics`

```

 es2015/modules/duplicate-named-export/input.js:2:9 parse/js ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

  ✖ `foo` has already been exported. Exported identifiers must be unique.

  ℹ Defined already here

  > 1 │ export { foo };
      │          ^^^
    2 │ export { bar as foo };

━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

✖ Found 1 problem

```