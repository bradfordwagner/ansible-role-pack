# bradfordwagner.ansible-role-pack

## Updating the version

Version is controlled by `pack_version` in `defaults/main.yml`.

Check for the latest release at: https://github.com/buildpacks/pack/releases

```yaml
pack_version: vX.Y.Z
```

## Renovate

Renovate (`bradfordwagner/renovate`, preset `ansible-role`) opens PRs for the version pins marked `# renovate:`, `meta/requirements.yml`, `config.yaml`'s `upstream.tag` and GitHub Actions. A merged PR labeled `release` is tagged with the next patch version and published to Galaxy by `.github/workflows/release.yml`.
