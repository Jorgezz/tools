# `index.test.ts`

**DO NOT MODIFY**. This file has been autogenerated. Run `rome test packages/@romejs/js-parser/index.test.ts --update-snapshots` to update.

## `esprima > invalid-syntax > migrated_0015`

```javascript
Program {
  comments: Array []
  corrupt: false
  directives: Array []
  filename: 'input.js'
  hasHoistedVars: false
  interpreter: undefined
  mtime: undefined
  sourceType: 'script'
  syntax: Array []
  loc: Object {
    filename: 'input.js'
    end: Object {
      column: 0
      index: 5
      line: 2
    }
    start: Object {
      column: 0
      index: 0
      line: 1
    }
  }
  diagnostics: Array [
    Object {
      origins: Array [Object {category: 'js-parser'}]
      description: Object {
        category: 'parse/js'
        message: PARTIAL_BLESSED_DIAGNOSTIC_MESSAGE {value: 'Expected a semicolon or a line terminator'}
      }
      location: Object {
        filename: 'input.js'
        mtime: undefined
        sourceType: 'script'
        end: Object {
          column: 3
          index: 3
          line: 1
        }
        start: Object {
          column: 3
          index: 3
          line: 1
        }
      }
    }
  ]
  body: Array [
    ExpressionStatement {
      loc: Object {
        filename: 'input.js'
        end: Object {
          column: 3
          index: 3
          line: 1
        }
        start: Object {
          column: 0
          index: 0
          line: 1
        }
      }
      expression: NumericLiteral {
        value: 1
        format: 'octal'
        loc: Object {
          filename: 'input.js'
          end: Object {
            column: 3
            index: 3
            line: 1
          }
          start: Object {
            column: 0
            index: 0
            line: 1
          }
        }
      }
    }
    ExpressionStatement {
      loc: Object {
        filename: 'input.js'
        end: Object {
          column: 4
          index: 4
          line: 1
        }
        start: Object {
          column: 3
          index: 3
          line: 1
        }
      }
      expression: NumericLiteral {
        value: 8
        format: undefined
        loc: Object {
          filename: 'input.js'
          end: Object {
            column: 4
            index: 4
            line: 1
          }
          start: Object {
            column: 3
            index: 3
            line: 1
          }
        }
      }
    }
  ]
}
```