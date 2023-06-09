# Инструкция по Git
## 1. Проверка наличия установленного Git
В терминале выполняем команду git version

Если Git установлен, появится сообщение с информацией о версии файла. Иначе будет сообщение об ошибке.

## 2. Настройка git
Открываем терминал и вводим две команды: 

git config --global user.name "<ваше_имя>"   
git config --global user.email "<адрес_почты>"

## 3. Инициализация репозитория
Открыть папку проекта используя команду открыть папку.

Затем, ввести команду git init, после чего появится сообщение с указанием пути открытой папки.

## 4. Сохранение изменений в файле
Вводим команду git commit чтобы сохранить изменения.

Если нужно, указываем комментарий с помощью команды git commit -m "<комментарий>".

## 5. Запись изменений в репозиторий
С помощью команды git add или git add --all добавляем необходимые для проекта файлы.

После правок, сохраняем изменения в файле и указываем комментарий с изменениями для дальнейшего понимания, с помощью команды:                        
get commit -m "<комментарий>".

## 6. Получение информации об истории commit
Вызов команды git log позволяет увидеть коммиты, сделанные в файле. 
Последние коммиты располагаются в порядке сверху вниз.
Последние коммиты располагаются в порядке сверху вниз.

## 7. Сравнение с последним коммитом
Команда git diff демонстрирует в терминале разницу между текущим файлом и сохраненным.

## 8. Перемещение между сохранениями
При вызове команды git checkout "<имя_сохранения>", которая позволяет перейти к предыдущей версии файла. Достаточно скопировать первые 4 символа имени чтобы git распознал нужное нам сохранение.

После переключения между разными версиями сохранения, можно вернуться на актуальную версию с помощью команды git checkout master.

## 9. Работа с удаленными репозиториями
1. Создали локальный репозиторий;
2. Выполнили (Push) нашего локального репозитория на сервис GitHub;
3. На сервисе GitHub открыли свой репозиторий и проверили правильность синхронизации (Все файлы нашего репозитория находятся на GitHub);
4. Можно открыть любой файл из нашего репозитория, просмотреть его, а также внести изменения;
5. Открыли нужный файл;
6. Нажали в контекстном меню "Карандаш" и редактируем файл;
7. В нижнем окне создаем коммит - таким образом мы делаем сохранения для перетягивания информации в локальный репозиторий.
8. Создаем Pull Request
