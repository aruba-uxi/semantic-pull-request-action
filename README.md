# Semantic Pull Request Action

Valid PR types are
```
- chore
- docs
- feat
- fix
- refactor
- revert
- security
- style
- test
```
          

And valid scopes are
```
- staging
- production
- client
- models
- streams
- requirements
- deps
```

A valid PR title has the form `<type><(optional:scope): <description>`, So the following, for example, are allowed PR titles:

`feat: add Polish language`

`fix(requirements): bump pydantic to version x.x.x`

`chore(deps): bump the general-updates group with 6 updates`

See https://www.conventionalcommits.org/en/v1.0.0/#specification for more information