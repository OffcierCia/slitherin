# Pessimistic plugin for slither

Some detectors to help with code review and audit process.

See the [detector documentation](https://github.com/trailofbits/slither/wiki/Adding-a-new-detector).

## Installation

Имея установленный slither, запускаем в папке репозитория команду

```bash
python3 setup.py develop
```

## Development

1. Вносим изменения в код детектора
2. Запускаем `slither` на тестовом файле, указав через флаг `--detect` название детектора.

Переустанавливать пагин каждый раз не нужно
