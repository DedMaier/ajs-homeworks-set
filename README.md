[![Build status](https://ci.appveyor.com/api/projects/status/yar77c51u0ky1a7c?svg=true)](https://ci.appveyor.com/project/DedMaier/ajs-homeworks-set)

## `Set`

### Легенда

Игрок может выбирать персонажей на конкретный раунд, исходя из их состояния, уровня и стратегии игры. Вам нужно не давать возможность добавлять в команду одного и того же персонажа несколько раз.

### Описание

Создайте класс `Team` с методами `add`, `addAll` и `toArray`. Класс должен хранить данные о персонажах команды в поле типа `Set`:
```javascript
class Team {
    constructor() {
        this.members = new Set();
    }
    ...
}
```

Метод `add` должен добавлять выбранного персонажа в команду (объект класса `Character`). При этом такой объект уже существует в команде — дублирования быть не должно, должна генерироваться ошибка.

Метод `addAll` должен добавлять произвольное количество персонажей в команду — используйте rest-parameters. Задвоения быть не должно, ошибка генерироваться **не должна**.

Метод `toArray` должен производить конвертацию `Set` в массив.

Не забудьте написать Unit-тесты, которые обеспечивают 100-процентное покрытие тестируемых функций и классов.

---

