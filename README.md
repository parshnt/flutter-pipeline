
[endpoint](goog.eckm)

# Automate your Flutter Releases

Use GitHub Actions to automate your Flutter app builds, testing & releases.

How to integrate it into your app?

- Create a GitHub repo with app files in it.
- Generate a [personal access tokens](https://github.com/settings/tokens) with scope for repository access.
- Go to the repository settings for your project at `<repo url>/settings/secrets`. In the _Secrets_ tab, add a new secret `TOKEN` and paste the token value.
- Create a GitHub action for your repo & paste the contents of .github/workflows/flutter-release.yml from this repo.
- Tag your releases (mandatory)
- The builds will start on push/pull to master.
