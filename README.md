# proto plugins

[proto](https://moonrepo.dev/proto) plugins for [SolidPing](https://github.com/fclairamb/solidping).

## sp

`sp` is the SolidPing CLI: manage checks, results and incidents from the terminal, or keep checks in a YAML manifest and reconcile them with `sp apply`.

```sh
proto plugin add sp "https://raw.githubusercontent.com/fclairamb/proto-plugins/main/sp.toml"
proto install sp
sp --version
```

Versions come from the `v*` tags of fclairamb/solidping. Downloads are checked against `sp-checksums.txt` from the same release.
