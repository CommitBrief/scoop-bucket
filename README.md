# CommitBrief Scoop Bucket

Scoop manifest for [CommitBrief](https://github.com/CommitBrief/commitbrief) —
the LLM-powered local code review CLI for git diffs.

## Install (Windows)

```pwsh
scoop bucket add commitbrief https://github.com/CommitBrief/scoop-bucket
scoop install commitbrief
```

Then run `commitbrief setup` to configure your provider and API key.

## How this repository works

This bucket is **populated automatically** by
[goreleaser](https://goreleaser.com/) on every public CommitBrief release.
Do not edit `bucket/commitbrief.json` by hand — your changes will be
overwritten on the next tag push. See the [release pipeline source][rel].

[rel]: https://github.com/CommitBrief/commitbrief/blob/main/.github/workflows/release.yml

## Reporting issues

CLI bugs and feature requests belong in the main
[commitbrief issue tracker](https://github.com/CommitBrief/commitbrief/issues).

Open issues here only for bucket-specific problems (e.g. the manifest is
broken or stale).

## License

The CommitBrief CLI is [GPL-3.0-or-later](https://github.com/CommitBrief/commitbrief/blob/main/LICENSE).
This bucket repository contains only build metadata and is licensed the
same way.
