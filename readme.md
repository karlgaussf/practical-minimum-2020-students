#### Задание 3.1  (lec03task01)(Pull request)
Если коротко, надо форкнуть репо, внести изменения, выслать пулл-реквест.

Теперь длиннее.
Для выполнения этого задания вам понадобится напарник.

Есть [репозиторий](https://github.com/cscenter/practical-minimum-2020-students) с простейшими математическими задачами. Доступ к нему можно получить пройдя по [ссылке](https://classroom.github.com/g/FRNzm-4B)   
Вам надо решить одну из них (задач),
придумать свою и заменить ей любой другой пример,      
а одну из них решить неправильно (дальше вы поймете зачем)

Для этого вы должны:

* Создать [тикет](https://github.com/cscenter/practical-minimum-2020-students/issues) (issue, ишью).
* Написать в заголовке свое имя и фамилию, в описании какой пример вы хотите решить и ссылку на профиль в csc (иначе вас сложно будет идентифицировать) .

* Сделать форк репозитория к себе .
* Сделать клон своего форка на свой компьютер .
* Создать ветку (есть хорошая практика начинать имя ветки с номера тикета) с вменяемым именем (в нашем случае лучше всего номер-тикета-имя-фамилия) .
* Решить пример (и сделать коммит). См. пример коммита ниже.
* Решить пример неправильно (и сделать коммит) .
* Внести изменения в любой другой нерешенный пример (и сделать коммит) .

Каждый commit message должен содержать номер тикета, пробел, содержать вменяемый текст. Например
```
ISSUE-37 Solve a task
```

**Имя тикета это набор букв в ВЕРХНЕМ регистре, знак тире и цифры**

Пара примеров

* `ISSUE-42`
* `HADOOP-312`
* `COVID-19`

Если вы уже что-то сделали не так, вам поможет `git rebase -i`.

Далее

* Сделать пулл реквест.
* Заголовок пулл-реквеста номер тикета и ваше имя, например `ISSUE-37 Ravil Galeyev`
* В описании пулл-реквеста, написать что вы сделали и ссылку на профиль в csc,
* Добавить в ревьюеры своего напарника.
* Ваш напарник должен найти неправильно решенный пример,
 * написать вам комментарий в пулл-реквесте,
 * вы должны поправить ошибку,
 * отписаться об этом в комментариях в пулл-реквесте,
 * Ваш напарнить должен нажать resolve на коментарии,
 * После этого ваш напарник ставит вам approve.

Теперь, когда все готово, можно добавить преподавателей в ревьюеры и приложить ссылки на свой пулл-реквест и на тот, где вы делали ревью, в комментарий к заданию.

Мержить в мастер можно после апрува от преподавателя, при мерже указать опцию squash, в commit message указать свое имя и фамилию. Например

```
ISSUE-37 Ravil Galeyev
```

Пока изменения не вмержены, вам придется притягивать (pull) изменения из master ветки и разрешать (возможные) конфликты.

При придумывании своего примера допускается использовать только два двузначных числа, знак + или -.

Решить пример значит дописать в строку “ = ${ответ}”,
например `21 + 21 = 42`

После мержа в мастер:

* Закрыть тикет
* Удалить ветку
