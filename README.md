[pre-commit](https://pre-commit.com/) hook for Flutter project

Add the following in your .pre-commit-config.yaml:

```yaml
  - repo: https://github.com/LqDeveloper/flutter_pre_commit
    rev: "main"
    hooks:
      - id: flutter-analyze
        args: [ lib/ ]
      - id: dart-format
        args: [ lib/ ]
      - id: dart-fix
        args: [ lib/ ]
```
