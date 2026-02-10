# dotnet dev-certs fails on GitHub Actions

Running this with .NET SDK Version 10.0.103 fails on GitHub Actions `ubuntu-latest` runner:

```
- name: Setup dev certs
run: |-
    dotnet dev-certs https --trust
```

- [.NET SDK 10.0.102 works](.github/workflows/dotnet-10.0.102.yml)
- [.NET SDK 10.0.103 fails](.github/workflows/dotnet-10.0.103.yml)
