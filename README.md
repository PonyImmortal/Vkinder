# 🤖**VKinder**

### Дипломная работа "VKinder"

## Задание

Используя данные из VK, нужно сделать сервис намного лучше, чем Tinder, а именно: чат-бота “VKinder”.

Бот должен искать людей, подходящих под условия, на основании информации о пользователе из VK:

* Возраст
* Пол
* Город
* Семейное положение

У тех людей, которые подошли по требованиям пользователю, получать топ-3 популярных фотографии профиля и отправлять их пользователю в чат вместе со ссылкой на найденного человека. Популярность определяется по количеству лайков и комментариев.

### Входные данные

Имя пользователя или его id в ВК, для которого мы ищем пару. Если информации недостаточно нужно дополнительно спросить её у пользователя.

### Требования к сервису:

* Код программы удовлетворяет PEP8.
* Получать токен от пользователя с нужными правами.
* Программа декомпозирована на функции/классы/модули/пакеты.
* Результат программы записывать в БД.
* Люди не должны повторяться при повторном поиске.
* Не запрещается использовать внешние библиотеки для vk.