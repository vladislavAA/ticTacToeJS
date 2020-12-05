# Описание проекта

Игра в "Крестики-нолики" (tic-tac-toe) с компьютером на поле произвольного размера (от 3x3 до 10x10).
Бот делает ход автоматически через 0.4 секунды после того, как Вы сделали ход.
Начинают ходить всегда крестики, кем играет человек определяется случайным образом.

* * *

* Информация о датах и исходах всех партий, а также о всех ходах, сделанных во время игры, должна сохраняться в базе данных indexedDB.
* Для каждой игры в базе хранится следующая информация:
	*Размер поля
	*Дата игры
	*Имя игрока
	*Какой фигурой играл человек
	*Какая фигура выиграла в партии
	Запись ходов в формате: номер хода | координата X | координата O
* В программе реализованы три режима, которым соответствуют кнопки в меню:
    * `Play`. Новая игра.
    * `List`. Вывод списка всех сохраненных игр.
    * `Replay`. Повтор игры с идентификатором id.


## Требования

Браузер с поддержкой JS

* * *

## Инструкция по установке и запуску игры

1. Перейти по ссылке https://vladislavaa.github.io/ticTacToeJS/
2. Приступить к игре
