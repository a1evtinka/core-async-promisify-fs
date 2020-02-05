# Промисификация fs

## Releases

### Pre-Release

Ты уже работал с модулем `fs`, однако ты делал это через `callbacks` либо сихронные методы. Синхронные методы в случае работы с внешними хранилищами не лучшая идея, а работа с коллбэками порой не удобна, да и выглядит страшновато, если они вкладываются друг в друга. К счастью у нас есть `Promises`! А это значит, что ты можешь обернуть наши асинхронные методы в промисы, и тогда работать с ними будет удобнее. Задание необходимо, чтобы ты разобрался в том, как работаю промисы и как писать свои функции, возвращающие промисы.

## Release 0:

Теперь твоей задачей будет написать свои методы работы с `fs` с использованием `Promise`.
Начни с `fs.readFile()`!

## Release 1:

Теперь используя промисы, напиши скрипт который приведет названия файлов в папке notes к формату `note\_%Дата создания%.txt`.
Для решения этой задачи тебе могут понадобиться такие методы `fs` как `fs.readdir()`,`fs.stat()` и `fs.rename()`.
