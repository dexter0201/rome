# `index.test.ts`

**DO NOT MODIFY**. This file has been autogenerated. Run `rome test internal/js-parser/index.test.ts --update-snapshots` to update.

## `es2015 > yield > parameter-name-arrow-inside-arrow-inside-generator`

### `ast`

```javascript
JSRoot {
	comments: Array []
	corrupt: false
	diagnostics: Array []
	directives: Array []
	filename: "es2015/yield/parameter-name-arrow-inside-arrow-inside-generator/input.js"
	hasHoistedVars: false
	interpreter: undefined
	mtime: undefined
	sourceType: "script"
	syntax: Array []
	loc: Object {
		filename: "es2015/yield/parameter-name-arrow-inside-arrow-inside-generator/input.js"
		end: Object {
			column: 1
			line: 3
		}
		start: Object {
			column: 0
			line: 1
		}
	}
	body: Array [
		JSFunctionDeclaration {
			id: JSBindingIdentifier {
				name: "fn"
				loc: Object {
					filename: "es2015/yield/parameter-name-arrow-inside-arrow-inside-generator/input.js"
					identifierName: "fn"
					end: Object {
						column: 12
						line: 1
					}
					start: Object {
						column: 10
						line: 1
					}
				}
			}
			loc: Object {
				filename: "es2015/yield/parameter-name-arrow-inside-arrow-inside-generator/input.js"
				end: Object {
					column: 1
					line: 3
				}
				start: Object {
					column: 0
					line: 1
				}
			}
			head: JSFunctionHead {
				async: false
				generator: true
				hasHoistedVars: false
				params: Array []
				rest: undefined
				returnType: undefined
				thisType: undefined
				typeParameters: undefined
				loc: Object {
					filename: "es2015/yield/parameter-name-arrow-inside-arrow-inside-generator/input.js"
					end: Object {
						column: 14
						line: 1
					}
					start: Object {
						column: 12
						line: 1
					}
				}
			}
			body: JSBlockStatement {
				directives: Array []
				loc: Object {
					filename: "es2015/yield/parameter-name-arrow-inside-arrow-inside-generator/input.js"
					end: Object {
						column: 1
						line: 3
					}
					start: Object {
						column: 15
						line: 1
					}
				}
				body: Array [
					JSExpressionStatement {
						loc: Object {
							filename: "es2015/yield/parameter-name-arrow-inside-arrow-inside-generator/input.js"
							end: Object {
								column: 22
								line: 2
							}
							start: Object {
								column: 2
								line: 2
							}
						}
						expression: JSArrowFunctionExpression {
							loc: Object {
								filename: "es2015/yield/parameter-name-arrow-inside-arrow-inside-generator/input.js"
								end: Object {
									column: 21
									line: 2
								}
								start: Object {
									column: 2
									line: 2
								}
							}
							head: JSFunctionHead {
								async: false
								hasHoistedVars: false
								params: Array []
								rest: undefined
								returnType: undefined
								thisType: undefined
								loc: Object {
									filename: "es2015/yield/parameter-name-arrow-inside-arrow-inside-generator/input.js"
									end: Object {
										column: 7
										line: 2
									}
									start: Object {
										column: 2
										line: 2
									}
								}
							}
							body: JSArrowFunctionExpression {
								loc: Object {
									filename: "es2015/yield/parameter-name-arrow-inside-arrow-inside-generator/input.js"
									end: Object {
										column: 21
										line: 2
									}
									start: Object {
										column: 8
										line: 2
									}
								}
								body: JSBlockStatement {
									body: Array []
									directives: Array []
									loc: Object {
										filename: "es2015/yield/parameter-name-arrow-inside-arrow-inside-generator/input.js"
										end: Object {
											column: 21
											line: 2
										}
										start: Object {
											column: 19
											line: 2
										}
									}
								}
								head: JSFunctionHead {
									async: false
									hasHoistedVars: false
									rest: undefined
									returnType: undefined
									thisType: undefined
									loc: Object {
										filename: "es2015/yield/parameter-name-arrow-inside-arrow-inside-generator/input.js"
										end: Object {
											column: 18
											line: 2
										}
										start: Object {
											column: 8
											line: 2
										}
									}
									params: Array [
										JSBindingIdentifier {
											name: "yield"
											loc: Object {
												filename: "es2015/yield/parameter-name-arrow-inside-arrow-inside-generator/input.js"
												identifierName: "yield"
												end: Object {
													column: 14
													line: 2
												}
												start: Object {
													column: 9
													line: 2
												}
											}
										}
									]
								}
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
