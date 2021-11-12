# seal-of-approval

Do you want to codify the criteria to merge a pull request, giving a signal to the developer that _“you may click the green button now”_ when all checks have passed?

Once all of the requirements are met, add this to your GitHub Actions workflow:

```yaml
      - uses: dtinth/seal-of-approval@v1
```

A seal of approval would be added to the PR under the checks section. It looks like this:

![image](https://user-images.githubusercontent.com/193136/141515134-79215e62-d56a-4d74-8313-c621ef4c0178.png)

Click on the _Details_ link to [see the seal of approval](https://github.com/dtinth/seal-of-approval/runs/4193009969).
