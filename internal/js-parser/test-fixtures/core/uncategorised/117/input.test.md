# `index.test.ts`

**DO NOT MODIFY**. This file has been autogenerated. Run `rome test internal/js-parser/index.test.ts --update-snapshots` to update.

## `core > uncategorised > 117`

### `ast`

```javascript
JSRoot {
	comments: Array []
	corrupt: false
	diagnostics: Array []
	directives: Array []
	filename: "core/uncategorised/117/input.js"
	hasHoistedVars: false
	interpreter: undefined
	mtime: undefined
	sourceType: "script"
	syntax: Array []
	loc: Object {
		filename: "core/uncategorised/117/input.js"
		end: Object {
			column: 13
			line: 1
		}
		start: Object {
			column: 0
			line: 1
		}
	}
	body: Array [
		JSExpressionStatement {
			loc: Object {
				filename: "core/uncategorised/117/input.js"
				end: Object {
					column: 13
					line: 1
				}
				start: Object {
					column: 0
					line: 1
				}
			}
			expression: JSCallExpression {
				loc: Object {
					filename: "core/uncategorised/117/input.js"
					end: Object {
						column: 13
						line: 1
					}
					start: Object {
						column: 0
						line: 1
					}
				}
				callee: JSReferenceIdentifier {
					name: "foo"
					loc: Object {
						filename: "core/uncategorised/117/input.js"
						identifierName: "foo"
						end: Object {
							column: 3
							line: 1
						}
						start: Object {
							column: 0
							line: 1
						}
					}
				}
				arguments: Array [
					JSReferenceIdentifier {
						name: "bar"
						loc: Object {
							filename: "core/uncategorised/117/input.js"
							identifierName: "bar"
							end: Object {
								column: 7
								line: 1
							}
							start: Object {
								column: 4
								line: 1
							}
						}
					}
					JSReferenceIdentifier {
						name: "baz"
						loc: Object {
							filename: "core/uncategorised/117/input.js"
							identifierName: "baz"
							end: Object {
								column: 12
								line: 1
							}
							start: Object {
								column: 9
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
