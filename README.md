# pedantic91

Попытка разработать собственный набор правил анализатора для унифицирования всех проектов. Реализация взята у гуглового пакета `pedantic`, так что если там будут breaking changes, то их также следует перенести сюда.

## Использование

Для использования правил добавьте dev зависимость в `pubspec.yaml`:

```yaml
dev_dependencies:
  pedantic91:
    git: git@github.com:ninenone/pedantic91.git
```

затем нужно включить его в ваш `analysis_options.yaml`.

```yaml
include: package:pedantic91/analysis_options.yaml
```
