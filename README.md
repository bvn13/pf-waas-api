# pf-waas-api

## Обновление Async API

### Предварительно установить библиотеку

``` bash
npm install -g @asyncapi/html-template@0.16.0
```

### Запустить пересборку HTML вручную

``` bash
cd async-api/site/
ag ../waas-async-api.yaml @asyncapi/html-template
```
NB! Перед тем, как запускать генерацию HTML нужно закоммитить все изменения в git.
И следовать всем инструкциям.

### Пересборка оформлена в виде скрипта (linux only)

> update-async-api.sh

