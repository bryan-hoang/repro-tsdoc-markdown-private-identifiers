# repro-tsdoc-markdown-private-identifiers

A reproduction of tsdoc-markdown treating private identifiers as public
identifiers.

To reproduce the issue:

```console
git clone https://github.com/bryan-hoang/repro-tsdoc-markdown-private-identifiers.git
cd repro-tsdoc-markdown-private-identifiers
npm clean-install
npm run repro
```

which generates the following documentation:

<!-- TSDOC_START -->

## :factory: LedgerCanister

### Methods

- [#shouldNoBeDocumented](#gear-#shouldnobedocumented)

#### :gear: #shouldNoBeDocumented

Private identifier method.

| Method | Type |
| ---------- | ---------- |
| `#shouldNoBeDocumented` | `() => void` |


<!-- TSDOC_END -->
