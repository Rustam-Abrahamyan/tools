# `index.test.ts`

**DO NOT MODIFY**. This file has been autogenerated. Run `rome test internal/js-parser/index.test.ts --update-snapshots` to update.

## `esprima > es2015-generator > static-generator-method`

### `ast`

```javascript
JSRoot {
	comments: Array []
	corrupt: false
	diagnostics: Array []
	directives: Array []
	filename: "esprima/es2015-generator/static-generator-method/input.js"
	hasHoistedVars: false
	interpreter: undefined
	mtime: undefined
	sourceType: "script"
	syntax: Array []
	loc: Object {
		filename: "esprima/es2015-generator/static-generator-method/input.js"
		end: Object {
			column: 0
			line: 2
		}
		start: Object {
			column: 0
			line: 1
		}
	}
	body: Array [
		JSClassDeclaration {
			id: JSBindingIdentifier {
				name: "Foo"
				loc: Object {
					filename: "esprima/es2015-generator/static-generator-method/input.js"
					identifierName: "Foo"
					end: Object {
						column: 9
						line: 1
					}
					start: Object {
						column: 6
						line: 1
					}
				}
			}
			loc: Object {
				filename: "esprima/es2015-generator/static-generator-method/input.js"
				end: Object {
					column: 30
					line: 1
				}
				start: Object {
					column: 0
					line: 1
				}
			}
			meta: JSClassHead {
				implements: undefined
				superClass: undefined
				superTypeParameters: undefined
				typeParameters: undefined
				loc: Object {
					filename: "esprima/es2015-generator/static-generator-method/input.js"
					end: Object {
						column: 30
						line: 1
					}
					start: Object {
						column: 0
						line: 1
					}
				}
				body: Array [
					JSClassMethod {
						kind: "method"
						key: JSStaticPropertyKey {
							value: JSIdentifier {
								name: "foo"
								loc: Object {
									filename: "esprima/es2015-generator/static-generator-method/input.js"
									identifierName: "foo"
									end: Object {
										column: 23
										line: 1
									}
									start: Object {
										column: 20
										line: 1
									}
								}
							}
							loc: Object {
								filename: "esprima/es2015-generator/static-generator-method/input.js"
								end: Object {
									column: 23
									line: 1
								}
								start: Object {
									column: 20
									line: 1
								}
							}
						}
						loc: Object {
							filename: "esprima/es2015-generator/static-generator-method/input.js"
							end: Object {
								column: 28
								line: 1
							}
							start: Object {
								column: 12
								line: 1
							}
						}
						body: JSBlockStatement {
							body: Array []
							directives: Array []
							loc: Object {
								filename: "esprima/es2015-generator/static-generator-method/input.js"
								end: Object {
									column: 28
									line: 1
								}
								start: Object {
									column: 26
									line: 1
								}
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
								filename: "esprima/es2015-generator/static-generator-method/input.js"
								end: Object {
									column: 25
									line: 1
								}
								start: Object {
									column: 23
									line: 1
								}
							}
						}
						meta: JSClassPropertyMeta {
							abstract: false
							accessibility: undefined
							optional: false
							readonly: false
							static: true
							typeAnnotation: undefined
							start: Object {
								column: 12
								line: 1
							}
							loc: Object {
								filename: "esprima/es2015-generator/static-generator-method/input.js"
								end: Object {
									column: 23
									line: 1
								}
								start: Object {
									column: 12
									line: 1
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