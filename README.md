# hello-act-max

This is my first GHE action.

## Notes
1. repo name shouldn't contain capital letter, like `helloAction`. otherwise 
`##[warning]Failed to download action 'https://api.github.com/repos/wxdlong/helloAction/tarball/master'. Error Response status code does not indicate success: 404 (Not Found).`

2. you should setup [two-factor-authentication](https://help.github.com/en/articles/configuring-two-factor-authentication) before publish

## Inputs

### `who-to-greet`

**Required** The name of the person to greet. Default `"maximus"`.

## Outputs

### `time`

The time we greeted you.

## Example usage

```yaml
uses: ghe-actions/hello-action@v<Tag>
with:
  who-to-greet: 'Mukul the Octocat'
```

## Contact

