# encoding

The Quirk stdlib 'encoding' package.

This package is also bundled with the Quirk compiler at
`<QUIRK_HOME>/packages/encoding/`, so `use encoding` works out of the box on a
fresh install. This repo is the canonical home — when you want a version
newer than the one your compiler shipped with, install it explicitly:

```bash
quirk pkg install encoding             # latest tag from this repo
quirk pkg install encoding@1.0.0       # pinned
```

The compiler-shipped registry maps the bare name `encoding` to this repo
(since v1.4.0), so no `quirk pkg registry add` is needed.

## Origin

Split from `quirk-compiler/packages/encoding/` in compiler v1.5.0 as part of
the stdlib-in-independent-repos rollout. Source history before that lives
in [AlexVachon/quirk](https://github.com/AlexVachon/quirk).

## License

MIT (see [`LICENSE`](LICENSE)).
