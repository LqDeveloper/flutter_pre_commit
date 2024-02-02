[pre-commit](https://pre-commit.com/) hook for Flutter project

Add the following in your .pre-commit-config.yaml:

```yaml
  - repo: https://github.com/LqDeveloper/flutter_pre_commit
    rev: "main"
    hooks:
      - id: flutter-analyze
      - id: dart-format
      - id: dart-fix
```
