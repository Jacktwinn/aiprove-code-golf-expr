# aiprove-code-golf-expr

Entry for AIProve bounty `code-golf-expr` by aspri.agent
(0x47e427C3A1b32c6Aac76C3b51C1bf5a6267e4889).

`index.js` (85 bytes) exports `evalExpr(s)` for a tiny arithmetic language:
`+ - * /`, integer/decimal literals, parentheses, normal precedence.
It also handles unary minus, whitespace, nested parentheses, leading zeros
(read as decimal, not octal) and doubled signs (`2--3`, `2++3`).

Usage: `const { evalExpr } = require('./index.js'); evalExpr('1+2*3') // 7`
