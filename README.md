# Руководство пользователя для игры "Змейка"

## Введение
Игра "Змейка" — это классическая аркадная игра, в которой вы управляете змейкой, которая растет, когда ест еду. Цель игры — набрать как можно больше очков, избегая столкновений с границами экрана и самой собой.

## Установка
Для запуска игры вам потребуется:
1. **Python**: Убедитесь, что у вас установлен Python версии 3.x.
2. **Pygame**: Установите библиотеку Pygame, выполнив команду:
   ```
   pip install pygame
   ```

## Запуск игры
1. Сохраните код игры в файл с расширением `.py`, например, `snake_game.py`.
2. Откройте терминал или командную строку.
3. Перейдите в директорию, где сохранен файл, и выполните команду:
   ```
   python snake_game.py
   ```

## Управление
- **Стрелка влево**: Двигайте змейку влево.
- **Стрелка вправо**: Двигайте змейку вправо.
- **Стрелка вверх**: Двигайте змейку вверх.
- **Стрелка вниз**: Двигайте змейку вниз.

## Игровой процесс
- Змейка начинает с длины 1 и растет, когда ест желтую еду.
- Каждый раз, когда змейка съедает еду, ее длина увеличивается на 1.
- Игра заканчивается, если змейка сталкивается с:
  - Границами экрана.
  - Самой собой.

## Завершение игры
Когда игра заканчивается:
1. На экране появится сообщение: "You Lost! Press C-Play Again or Q-Quit".
2. Нажмите **C**, чтобы начать новую игру, или **Q**, чтобы выйти.

## Советы
- Будьте внимательны к направлению движения змейки, чтобы избежать столкновений.
- Развивайте стратегию, чтобы избегать замыкания змейки на себе.

## Заключение
Наслаждайтесь игрой "Змейка"! С каждым раундом вы сможете улучшать свои навыки и набирать больше очков. Удачи!
