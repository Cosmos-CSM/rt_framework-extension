# *> Package Name <*

A repository for a framweork extensions package. Framweork extensions are CSM shaped utilities and tools for frameworks and languages used during development.

[Changelog](> CHANGELOG file link <)

## **Installation & Usage**

// --> Example for NuGet based packages.

> dotnet nuget add source --name "github" --username {*GITHUB.USR*} --password {*GITHUB.PAT*} "<https://nuget.pkg.github.com/Cosmos-CSM/index.json>"

* GITHUB.USR: It's your github user account.

* GITHUB.PAT: It's a generated personal access token, go to *Settings* > *Developer Settings* > *Personal access tokens*, create a **Classic** type access token and provide at minimum **Read:Packages** permission.

> dotnet add package **<PackageId>** --source github

// --> Example for Dart based packages.

> In your solution's **pubspec.yaml** file under *dependencies* add:

```yaml
<package_id>:
  git:
    path: ./<package_path>
    url: <repository_url>
    version: <version>
```

*Version* can be found in the GitHub repository page at *Releases* section, for more details about each version content please consult **CHANGELOG.md**
