
<p align="center">
  <a href="https://github.com/miyajan/javascript-action-pr-comment"><img alt="GitHub Actions status" src="https://github.com/miyajan/javascript-action-pr-comment/workflows/test-local/badge.svg"></a>
</p>

# PR Comment Action

This action comments a message on PR.

## Inputs

### `message`

**Required** The message to comment on PR.

## Outputs

### `commentUrl`

The comment URL.

## Environment Variables

### `GITHUB_TOKEN`

**Required** The GitHub Token for comment on PR.

## Example Usage

```yaml
uses: miyajan/javascript-action-pr-comment@v1
env:
  GITHUB_TOKEN: ${{ secrets.GITHUB_TOKEN }}
with:
  message: Nice PR!👍
```
