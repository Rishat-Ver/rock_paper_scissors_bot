# **Телеграм бот "Камень, ножницы, бумага"**

### **Что бот должен уметь?**

* Отправлять пользователю клавиатуру с обычными кнопками выбора: камень, ножницы, бумага<>
* Генерировать случайный элемент в игре из списка "камень, ножницы, бумага"
* Обрабатывать выбор пользователя и сообщать, кто победил

### **Дополнительный функционал**

Не предусмотрен

### **Описание взаимодействия с ботом**

1. Пользователь отправляет команду /start боту (или стартует его, найдя в поиске)
2. Бот приветствует пользователя и предлагает сыграть в игру "Камень, ножницы, бумага", отправляя клавиатуру с ответами "Давай!" и "Не хочу!", а также предлагает пользователю прочитать подробные правила, отправив команду /help
3. На этом этапе пользователь может совершить 4 действия:
    - Согласиться играть с ботом в игру, нажав на обычную кнопку "Давай!" <br>
    - Не согласиться играть с ботом, нажав на обычную кнопку "Не хочу!" <br>
    - Отправить в чат команду /help <br>
    - Отправить в чат любое другое сообщение <br>
4. Пользователь нажимает на обычную кнопку "Давай!":
    - Бот присылает в чат сообщение "Отлично! Делай свой выбор!"
    - Бот отправляет в чат клавиатуру с кнопками выбора "Камень", "Ножницы" и "Бумага" <br>
    - На этом этапе пользователь может совершить 3 действия: <br>
        - Нажать на одну из кнопок выбора ("Камень", "Ножницы" или "Бумага") <br>
        - Отправить в чат команду /help <br>
        - Отправить в чат любое другое сообщение <br>
    - Пользователь нажимает на одну из кнопок выбора ("Камень", "Ножницы" или "Бумага"):
        - Бот генерирует случайный ответ из того же списка <br>
        - Бот проверяет кто победил <br>
        - Бот сообщает пользователю кто победил <br>
        - Бот отправляет пользователю предложение сыграть еще раз и клавиатуру для выбора с кнопками "Давай!" и "Не хочу!" <br>
5. Пользователь нажимает на кнопку "Не хочу!":
    - Клавиатура сворачивается <br>
    - Бот присылает сообщение "Хорошо. Если, вдруг, захочешь сыграть - открой клавиатуру и нажми "Давай!" <br>
6. Пользователь отправляет в чат команду /help:
    - Бот присылает в чат правила игры, предложение сыграть и клавиатуру с кнопками "Давай!" и "Не хочу!" .br
7. Пользователь отправляет в чат любое другое сообщение:
    - Бот присылает в чат сообщение, что не понимает пользователя