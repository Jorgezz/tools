# `index.test.ts`

**DO NOT MODIFY**. This file has been autogenerated. Run `rome test packages/js-parser/index.test.ts --update-snapshots` to update.

## `experimental > module-attributes > valid-syntax-without-attributes`

### `ast`

```javascript
JSRoot {
	comments: Array []
	corrupt: false
	diagnostics: Array []
	directives: Array []
	filename: "experimental/module-attributes/valid-syntax-without-attributes/input.js"
	hasHoistedVars: false
	interpreter: undefined
	mtime: undefined
	sourceType: "module"
	syntax: Array []
	loc: Object {
		filename: "experimental/module-attributes/valid-syntax-without-attributes/input.js"
		end: Object {
			column: 0
			index: 28
			line: 2
		}
		start: Object {
			column: 0
			index: 0
			line: 1
		}
	}
	body: Array [
		JSImportDeclaration {
			importKind: undefined
			namedSpecifiers: Array []
			namespaceSpecifier: undefined
			loc: Object {
				filename: "experimental/module-attributes/valid-syntax-without-attributes/input.js"
				end: Object {
					column: 27
					index: 27
					line: 1
				}
				start: Object {
					column: 0
					index: 0
					line: 1
				}
			}
			source: JSStringLiteral {
				value: "foo.json"
				loc: Object {
					filename: "experimental/module-attributes/valid-syntax-without-attributes/input.js"
					end: Object {
						column: 26
						index: 26
						line: 1
					}
					start: Object {
						column: 16
						index: 16
						line: 1
					}
				}
			}
			defaultSpecifier: JSImportDefaultSpecifier {
				loc: Object {
					filename: "experimental/module-attributes/valid-syntax-without-attributes/input.js"
					end: Object {
						column: 10
						index: 10
						line: 1
					}
					start: Object {
						column: 0
						index: 0
						line: 1
					}
				}
				local: JSImportSpecifierLocal {
					name: JSBindingIdentifier {
						name: "foo"
						loc: Object {
							filename: "experimental/module-attributes/valid-syntax-without-attributes/input.js"
							identifierName: "foo"
							end: Object {
								column: 10
								index: 10
								line: 1
							}
							start: Object {
								column: 7
								index: 7
								line: 1
							}
						}
					}
					importKind: undefined
					loc: Object {
						filename: "experimental/module-attributes/valid-syntax-without-attributes/input.js"
						end: Object {
							column: 10
							index: 10
							line: 1
						}
						start: Object {
							column: 7
							index: 7
							line: 1
						}
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