# pnpm

Configuration file locations:

- `pnpm-workspace.yaml`
- Global configuration: `~\AppData\Local\pnpm\config\config.yaml`

`pnpm-workspace.yaml` :

```yaml
minimumReleaseAge: 10080
registries:
  default: https://npm.flatt.tech/
trustPolicy: no-downgrade
```

参考:
- https://pnpm.io/ja/settings
- https://shisho.dev/docs/ja/t/guard/quickstart/npm
