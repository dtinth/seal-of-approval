# seal-of-approval

Do you want to codify the criteria to merge a pull request, giving a signal to the developer that _“you may click the green button now”_ when all checks have passed?

Once all of the requirements are met, add this to your GitHub Actions workflow:

```yaml
      - uses: dtinth/seal-of-approval@v1
```

A seal of approval would be added to the PR under the checks section.
