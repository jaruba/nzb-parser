# NZB Parser

Usage

```ts
import parse from 'nzb-parser'

const res = await fetch('https://example.com/file.nzb')
const nzb = parse(await res.text())

const files = nzb.files
```