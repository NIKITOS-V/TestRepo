# Git команды

## Просмотр данных

Файлов в директории
```text
dir
```
Имени пользователя
```text
git config user.name
```

Почты пользователя
```text
git config user.email
```

Статуса репозитория
```text
git status
```

Истории коммитов
```text
git log
```

Истории коммитов в упрощённом виде
```text
git log --oneline
```

## Изменение значений

Папки директории
```text
cd Полный_путь_до_файла
```

Имени пользователя
```text
git config --global user.name 'Nik'
```

Почты пользователя
```text
git config --global user.email 'example@mail.ru'
```

Инициализация локального репозитория некоторых конфигурационных файлов Git (_init_)
```text
git init
```

Индексация файла
```text
git add Имя_Файла
```

Фиксация файла (добавление в *Commit*)
```text
git commit -m 'комментарий'
```

Удаление файла
```text
del Имя_Файла
```

Возврат в последнее состояние директории
```text
git checkout master
```

Переход в определённую стадию коммит
```text
git checkout Уникальный_номер_коммит
```
