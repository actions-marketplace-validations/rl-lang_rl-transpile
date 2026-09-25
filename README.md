# rl-transpile

Transpiles a `.rl` file to C with `rlt`.

```yaml
- uses: rl-lang/rl-transpile@main
  with:
    file: src/main.rl
    compile: true   # also build a binary
```

| Input | Default |
|---|---|
| `version` | `latest` |
| `file` | *(required)* |
| `output` | `''` |
| `compile` | `false` |
| `test` | `false` |
| `opt` | `''` |

`test: true` emits the test-driver main instead of the program main.
