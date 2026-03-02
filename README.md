# cmux Intel Mac Builds

Automated Intel Mac (x86_64) builds of [cmux](https://github.com/manaflow-ai/cmux).

Upstream releases are checked every 6 hours. When a new release is detected, an unsigned x86_64 build is created and published as a GitHub release.

## Download

See [Releases](https://github.com/webkaz/cmux-intel-builds/releases).

Since the builds are unsigned, on first launch:

```sh
xattr -cr /Applications/cmux.app
```

Or right-click the app and select "Open".
