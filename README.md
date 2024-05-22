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
```

A valid PR title has the form `<type><(optional:scope)>: <description>`, So the following, for example, are allowed PR titles:

- `feat: add Polish language`
- `fix(requirements): bump pydantic to version x.x.x`

See https://www.conventionalcommits.org/en/v1.0.0/#specification for more information