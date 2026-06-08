### Basics

| #  | File | Concept |
|----|------|---------|
| 01 | [`daml/Basics/HelloWorld.daml`](daml/Basics/HelloWorld.daml) | Template = schema, contract = row; `signatory`; create & query in a Script |
| 02 | [`daml/Basics/Counter.daml`](daml/Basics/Counter.daml) | The "First App". No mutable state -> change = archive + recreate. Consuming vs `nonconsuming` choices; `submitMustFail` |
| 03 | [`daml/Basics/Primitives.daml`](daml/Basics/Primitives.daml) | Int / Decimal / Text / Party / Time / Date / Optional / lists. |
| 04 | [`daml/Basics/Authorization.daml`](daml/Basics/Authorization.daml) | No `msg.sender`: `signatory` / `observer` / `controller`. `ensure` invariants and per-contract privacy |
| 05 | [`daml/Basics/ProposeAccept.daml`](daml/Basics/ProposeAccept.daml) | The core idiom: how a two-signatory contract gets created without forging authority |
