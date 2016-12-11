# Chess Test

## Задание:
Существует шахматная доска определенного размера.
На эту доску можно добавлять различные фигуры (пешки/ферзи/короли).
После добавления фигуры можно перемещать или удалять.
В любой момент времени состояние доски можно сохранить в хранилище (или загрузить из него): в файл или в redis.

Необходимо реализовать описанную выше функциональность.
При реализации учтите, что фигур может быть больше, чем три вида; виды хранилищ могут меняться.
Добавьте возможность вызова пользовательского кода в момент,
когда на доску добавляется фигура определенного типа/фигура любого типа (например,
выводить текстовое сообщение при добавлении пешки / при добавлении любой фигуры).

## Сборка

```sh
composer install
```

## Запуск:

```sh
./vendor/bin/phpunit src/BoardTest.php
```