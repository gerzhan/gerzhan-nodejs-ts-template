# Инициализация репозитория

## Цель

- настроить SCV для хранения кода

## Реализация

- создание диреткории для репотзтория-шаблона

```bash
$mkdir gerzhan-nodejs-ts-template
$cd gerzhan-nodejs-ts-template
```

- инициализация `git`

```bash
$git init
```

- добавить файл с описание репозитория

```bash
$echo "# NodeJS + TypeScript Template" >> README.md
```

- зафиксировать изменения в репозитории

```bash
$git add -A
$git commit -m ":star: Start project"
```

- создать репозиторий на github [gerzhan/gerzhan-nodejs-ts-template](https://github.com/gerzhan/gerzhan-nodejs-ts-template)

- настроить удаленный репозиторий для локального репозитория

```bash
$git remote add origin https://github.com/gerzhan/gerzhan-nodejs-ts-template.git
$git branch -M main
$git push -u origin main
```

- указать в [настойках github репозитория](https://github.com/gerzhan/gerzhan-nodejs-ts-template/settings)

| `Template repository` | on  |
| --------------------- | --- |

## Итог

- создан локальный репозиторий для шаблона-заготовки проектов на NodeJS + TypeScript
- настроен удаленный репозиторий для хранения шаблона-заготовки для создания новых проектов
