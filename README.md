# .github

This repository is being used to share repository configurations in `.github/settings.yml` files. For this file to work, the [`repository-settings`](https://github.com/repository-settings/app) app needs to be enabled.

The below can be used to create a `settings.yml` file that extends the one in this repository:

```
# https://github.com/brianespinosa/.github
_extends: .github

repository:

  # The name of the repository. Changing this will rename the repository
  name: <name>

  # A short description of the repository that will show up on GitHub
  description: <description>

  # A URL with more information about the repository
  homepage: <url>

  # A comma-separated list of topics to set on the repository
  topics: react, nextjs

  # Either `true` to make the repository private, or `false` to make it public.
  private: false
```
