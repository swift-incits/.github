# Swift INCITS

Swift implementations of INCITS (InterNational Committee for Information Technology Standards) specifications — a per-authority organization of [swift-standards](https://github.com/swift-standards), Layer 2 of the [Swift Institute](https://github.com/swift-institute) ecosystem.

## What this is

One package per specification, named `swift-incits-<number>`. Each package implements its source document as literally as possible — parsing, validation, and formatting enforced by Swift's type system — and defines its own namespace (`INCITS_4_1986`). Where several specifications govern one subject, the unifying `swift-*-standard` package lives in [swift-standards](https://github.com/swift-standards).

> Swift INCITS is an independent open-source project. It is not affiliated with, endorsed by, or sponsored by INCITS.

## Repositories

Every repository description carries the specification's full title. Browse the complete
collection in the [repositories tab](https://github.com/orgs/swift-incits/repositories), or
use GitHub's repository search to filter it by topic, language, or other repository metadata.

## Status

Public alpha. Maintained by [Coen ten Thije Boonkkamp](https://github.com/coenttb) — contributions welcome via pull request.

## License

All packages use the Apache License 2.0.
