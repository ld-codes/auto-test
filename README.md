# auto-test

This repository is to test [auto tool](https://github.com/intuit/auto)

## How-to

1. Push some commits to develop branch

2. Create a PR from develop to main

3. Add "release" and "major"/"minor"/"patch" labels to the PR

4. Merge the PR

5. Checkout to main locally

```
$ git checkout main
$ git pull
```

6. Create a new tag

```
$ git tag v[x.y.z]
$ git tag --push
```

7. Release

```
$ npx auto release
```
