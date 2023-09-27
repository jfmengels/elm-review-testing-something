# elm-review-testing-something

ioiezijf

Provides [`elm-review`](https://package.elm-lang.org/packages/jfmengels/elm-review/latest/) rules to REPLACEME.

## Provided rules

- [`Not.A.Rule`](https://package.elm-lang.org/packages/jfmengels/elm-review-testing-something/1.0.0/Not-A-Rule) - Reports REPLACEME.

## Configuration

```elm
module ReviewConfig exposing (config)

import Not.A.Rule
import Review.Rule exposing (Rule)

config : List Rule
config =
    [ Not.A.Rule.rule
    ]
```

## Try it out

You can try the example configuration above out by running the following command:

```bash
elm-review --template jfmengels/elm-review-testing-something/example
```
