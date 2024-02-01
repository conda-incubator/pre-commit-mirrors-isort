# isort pre-commit hook

pre-commit hook of isort with conda as a `language` / package manager.

For pre-commit: see [here](https://github.com/pre-commit/pre-commit)

For isort: see [here](https://github.com/timothycrosley/isort)

## Using isort with pre-commit and conda:

Add this to your `.pre-commit-config.yaml`

```yaml
 - repo: https://github.com/quantco/pre-commit-mirrors-isort
   rev: ''  # Use the sha / tag you want to point at
   hooks:
     - id: isort-conda
```
