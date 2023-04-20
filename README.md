# HW_Unit28_test_authorization_page
test_authorization_page

Итоговый проект по автоматизации тестирования. Объект тестирования: https://b2c.passport.rt.ru

Заказчик передал вам следующее задание:

Протестировать требования. Разработать тест-кейсы (не менее 15). Необходимо применить несколько техник тест-дизайна. Провести автоматизированное тестирование продукта (не менее 15 автотестов). Заказчик ожидает по одному автотесту на каждый написанный тест-кейс. Оформите свой набор автотестов в GitHub. Оформить описание обнаруженных дефектов. Во время обучения вы работали с разными сервисами и шаблонами, используйте их для оформления тест-кейсов и обнаруженных дефектов.

Перечислены инструменты, которые применялись для тестирования
Почему именно этот инструмент и эту технику. Что им проверялось. Что именно в нем сделано.

Техники:
Классы эквивалентности использованы для сокращения количиства параметров. Провекра форм ввода имени и фамилии, например, тест "Форма ввода имени - валидное имя".
Граничные значения использованы для проверки граничных значений формы для ввода имени и фамилии. Например, тест "Форма ввода имени невалидное имя".
Предугадывание ошибки на основе опыта. Описаны возможные ошибки. Например,тест "Форма ввода имени - валидное имя из 2 символов и с символом '-' "
Тестирование состояний и переходов. Использовано для проверки соответствия заявленным требованиям. Например, тест "При вводе номера телефона/почты/логина/лицевого счета - таб выбора телефонной аутентификации меняется автоматически. "
Попарное тестировани. Использовано для проверки пар имя и фамилия. Например, тест "Формы ввода имени и фамилии - валидные данные"
Тестирование по сценарию использования. Применено для отработки необходимых действий пользователя для регистрации. Например, тест "Зарегистрироваться на странице авторизации"

Код написан в PyCharm. В основе лежит Smart Page Object. Изменены отдельные фикстуры. Добавлены драйверы для браузеров Chrome, Yandex, Firefox (можно выбрать нужный). 
Для авторизации используется 3 класса: AuthPage для авторизации с паролем, RegPage переход на страницу регистрации, MainPage для авторизации с куки.
