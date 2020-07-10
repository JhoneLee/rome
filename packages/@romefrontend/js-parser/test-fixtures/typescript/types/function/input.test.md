# `index.test.ts`

**DO NOT MODIFY**. This file has been autogenerated. Run `rome test packages/@romefrontend/js-parser/index.test.ts --update-snapshots` to update.

## `typescript > types > function`

### `ast`

```javascript
JSRoot {
	comments: Array []
	corrupt: false
	diagnostics: Array []
	directives: Array []
	filename: "input.ts"
	hasHoistedVars: false
	interpreter: undefined
	mtime: undefined
	sourceType: "module"
	syntax: Array ["ts"]
	loc: Object {
		filename: "input.ts"
		end: Object {
			column: 0
			index: 56
			line: 2
		}
		start: Object {
			column: 0
			index: 0
			line: 1
		}
	}
	body: Array [
		JSVariableDeclarationStatement {
			loc: Object {
				filename: "input.ts"
				end: Object {
					column: 55
					index: 55
					line: 1
				}
				start: Object {
					column: 0
					index: 0
					line: 1
				}
			}
			declaration: JSVariableDeclaration {
				kind: "let"
				loc: Object {
					filename: "input.ts"
					end: Object {
						column: 55
						index: 55
						line: 1
					}
					start: Object {
						column: 0
						index: 0
						line: 1
					}
				}
				declarations: Array [
					JSVariableDeclarator {
						id: JSBindingIdentifier {
							name: "f"
							loc: Object {
								filename: "input.ts"
								end: Object {
									column: 54
									index: 54
									line: 1
								}
								start: Object {
									column: 4
									index: 4
									line: 1
								}
							}
							meta: JSPatternMeta {
								definite: undefined
								loc: Object {
									filename: "input.ts"
									end: Object {
										column: 54
										index: 54
										line: 1
									}
									start: Object {
										column: 4
										index: 4
										line: 1
									}
								}
								typeAnnotation: TSFunctionType {
									loc: Object {
										filename: "input.ts"
										end: Object {
											column: 54
											index: 54
											line: 1
										}
										start: Object {
											column: 7
											index: 7
											line: 1
										}
									}
									typeAnnotation: TSVoidKeywordTypeAnnotation {
										loc: Object {
											filename: "input.ts"
											end: Object {
												column: 54
												index: 54
												line: 1
											}
											start: Object {
												column: 50
												index: 50
												line: 1
											}
										}
									}
									meta: TSSignatureDeclarationMeta {
										typeParameters: undefined
										loc: Object {
											filename: "input.ts"
											end: Object {
												column: 54
												index: 54
												line: 1
											}
											start: Object {
												column: 7
												index: 7
												line: 1
											}
										}
										rest: JSBindingIdentifier {
											name: "c"
											loc: Object {
												filename: "input.ts"
												identifierName: "c"
												end: Object {
													column: 35
													index: 35
													line: 1
												}
												start: Object {
													column: 34
													index: 34
													line: 1
												}
											}
											meta: JSPatternMeta {
												optional: undefined
												loc: Object {
													filename: "input.ts"
													end: Object {
														column: 45
														index: 45
														line: 1
													}
													start: Object {
														column: 34
														index: 34
														line: 1
													}
												}
												typeAnnotation: TSArrayType {
													loc: Object {
														filename: "input.ts"
														end: Object {
															column: 45
															index: 45
															line: 1
														}
														start: Object {
															column: 37
															index: 37
															line: 1
														}
													}
													elementType: TSNumberKeywordTypeAnnotation {
														loc: Object {
															filename: "input.ts"
															end: Object {
																column: 43
																index: 43
																line: 1
															}
															start: Object {
																column: 37
																index: 37
																line: 1
															}
														}
													}
												}
											}
										}
										parameters: Array [
											JSBindingIdentifier {
												name: "a"
												loc: Object {
													filename: "input.ts"
													identifierName: "a"
													end: Object {
														column: 9
														index: 9
														line: 1
													}
													start: Object {
														column: 8
														index: 8
														line: 1
													}
												}
												meta: JSPatternMeta {
													optional: undefined
													loc: Object {
														filename: "input.ts"
														end: Object {
															column: 17
															index: 17
															line: 1
														}
														start: Object {
															column: 8
															index: 8
															line: 1
														}
													}
													typeAnnotation: TSNumberKeywordTypeAnnotation {
														loc: Object {
															filename: "input.ts"
															end: Object {
																column: 17
																index: 17
																line: 1
															}
															start: Object {
																column: 11
																index: 11
																line: 1
															}
														}
													}
												}
											}
											JSBindingIdentifier {
												name: "b"
												loc: Object {
													filename: "input.ts"
													identifierName: "b"
													end: Object {
														column: 20
														index: 20
														line: 1
													}
													start: Object {
														column: 19
														index: 19
														line: 1
													}
												}
												meta: JSPatternMeta {
													optional: true
													loc: Object {
														filename: "input.ts"
														end: Object {
															column: 29
															index: 29
															line: 1
														}
														start: Object {
															column: 19
															index: 19
															line: 1
														}
													}
													typeAnnotation: TSNumberKeywordTypeAnnotation {
														loc: Object {
															filename: "input.ts"
															end: Object {
																column: 29
																index: 29
																line: 1
															}
															start: Object {
																column: 23
																index: 23
																line: 1
															}
														}
													}
												}
											}
										]
									}
								}
							}
						}
						init: undefined
						loc: Object {
							filename: "input.ts"
							end: Object {
								column: 54
								index: 54
								line: 1
							}
							start: Object {
								column: 4
								index: 4
								line: 1
							}
						}
					}
				]
			}
		}
	]
}
```

### `diagnostics`

```
✔ No known problems!

```