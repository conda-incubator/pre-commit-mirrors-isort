isort(-conda) mirror
===================

Mirror of isort for pre-commit with conda as a language.

* For pre-commit: see https://github.com/pre-commit/pre-commit
* For isort: see https://github.com/timothycrosley/isort

### Using isort with pre-commit and conda:

Add this to your `.pre-commit-config.yaml`

```yaml
 - repo: https://github.com/Quantco/pre-commit-mirrors-isort
   rev: ''  # Use the sha / tag you want to point at
   hooks:
     - id: isort-conda
```

