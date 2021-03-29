# GitHub Action: Pull Request Assignee

Assigns a Pull Request to the person who created it, if they belong to the organization
and have `push` permission in the repository.

[github actions]: https://help.github.com/en/actions "GitHub Actions Documentation"

## Usage

You can use it on a repository through [GitHub Actions][]:

```yaml
- uses: itsmycargo/github-action-pr-assignee@master
  with:
    # Auth token to interact with the GitHub API (automatically generated).
    # Default: ${{ github.token }}
    token: ''
```

### Example

```yaml
- uses: itsmycargo/github-action-pr-assignee@master
```

## Developing

To build and run run all checks:

```bash
$ npm install
$ npm run all
...
```
