# notepad
notepad = это Ruby программа, которая при запуске позволяет хранить записи трех типов: -Link (Ссылка). -Memo (Памятка). -Task (Задача).

Инструкция по использованию программы

1. Открыть консоль
2. Установите бандлер

```html
    gem install bundler 2.2.21
```

3. Установите гемы при помощи бандла

```html
    bundle install
```

4. Для запуска напишите:

```html
    ruby notepad.rb
```

5. Чтобы красиво вывести заметки:

```html
    ruby read.rb
```

Опциональные ключи
У ```read.rb``` имеются опциональные ключи реализованные через optparse:

```--type``` - какой тип постов показывать

```--id``` - показать подробнее конкретный id

```--limit``` - сколько последних постов показать
