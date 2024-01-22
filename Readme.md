# Промежуточная контрольная работа по блоку специализация

## Задание 1. Приложение заметки (Python)

# Информация о проекте
Необходимо написать проект, содержащий функционал работы с заметками.
Программа должна уметь создавать заметку, сохранять её, читать список
заметок, редактировать заметку, удалять заметку.

# Как сдавать проект
Для сдачи проекта необходимо создать отдельный общедоступный
репозиторий (Github, gitlub, или Bitbucket). Разработку вести в этом
репозитории, использовать пул реквесты на изменения. Программа должна
запускаться и работать, ошибок при выполнении программы быть не должно.

# Задание
Реализовать консольное приложение заметки, с сохранением, чтением,
добавлением, редактированием и удалением заметок. Заметка должна
содержать идентификатор, заголовок, тело заметки и дату/время создания или
последнего изменения заметки. Сохранение заметок необходимо сделать в
формате json или csv формат (разделение полей рекомендуется делать через
точку с запятой). Реализацию пользовательского интерфейса студент может
делать как ему удобнее, можно делать как параметры запуска программы
(команда, данные), можно делать как запрос команды с консоли и
последующим вводом данных, как-то ещё, на усмотрение студента.
Например:

*python notes.py add --title "новая заметка" –msg "тело новой заметки"*

Или так:

python note.py
*Введите команду: add*
*Введите заголовок заметки: новая заметка*
*Введите тело заметки: тело новой заметки*
*Заметка успешно сохранена*

Введите команду:
При чтении списка заметок реализовать фильтрацию по дате.

# Критерии оценки
Приложение должно запускаться без ошибок, должно уметь сохранять данные
в файл, уметь читать данные из файла, делать выборку по дате, выводить на
экран выбранную запись, выводить на экран весь список записок, добавлять
записку, редактировать ее и удалять.