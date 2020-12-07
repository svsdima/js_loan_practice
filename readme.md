# Многостраничный сайт и скрипты полностью в ООП стиле

## Знакомство с проектом и реализация главного слайдера
Страница index.html должна быть реализована в виде большого слайдера, где каждый слайд - на всю страницу. Переключение страниц идёт только вперёд при помощи клика на стрелку. При клике на логотип - идёт переход к первому слайду.

Страница modules.html должна быть реализована аналогичным образом. Кроме этого, необходимо реализовать навигацию под контентом модуля.

- Создаю в папке js папку modules
- В папке modules создаю файл slider.js
- Прописав скрипты не забыть импортировать в main.js

## Всплывающий со временем блок
Этот блок необходимо показать через 3 секунды после того, как человек попадает на страницу.

- В slider.js прописываем код.
- Прописав скрипты не забыть импортировать в main.js

## Создаем видеоплеер в модальном окне
На первом экране при клике на кнопку с классом play необходимо показать блок с классом overlay и показать необходимое видео, ссылка на которое в data-url у кнопки, которую нажал пользователь. Учтите, что этот скрипт должен быть универсальным и менял видео в зависимости от кнопки. Также при клике на крестик необходимо полностью закрыть модальное окно.

- В папке modules создаю файл playVideo.js
- Прописав скрипты не забыть импортировать в main.js

## Наследование классов. Создаем общий прототип слайдера и главные слайдеры

- Делаем рефакторинг кода в slider.js
- В папке modules создаю папку slider и перекидываю туда slider.js
- В папке slider создаю файл slider-main.js
- Прописав скрипты не забыть импортировать в main.js

## Реализация вторичных слайдеров (меньших размеров)
На первом экране есть слайдер с модулями. Необходимо его реализовать: стрелки для переключения слайдов.
На третьей странице необходимо реализовать слайдер. В самом слайдере необходимо автоматическое перелистывание каждые 5 секунд.
На пятой странице реализовать слайдер.

- В папке slider создаю файл slider-mini.js
- Прописав скрипты не забыть импортировать в main.js

## Реализация блока с различиями
На второй странице есть список различий.
Изначально оба списка должны выглядеть как показано в позиции 1.
При клике на крестик открывается следующий шаг - добавление карточки спереди, карточка "click to show" смещается ниже.
При появлении на третьей карточки - карточка "click to show" исчезает. Желаетльно применить анимацию, аналогичную fadeIn.

- В папке modules создаю файл difference.js
- Прописав скрипты не забыть импортировать в main.js

## Работаем с формами отправки данных
Необходимо реализовать форму отправки без перезагрузки страницы.
Должны передаваться все выбранные/введенные данные.
Необходимо запретить ввод кириллицы в поле Email.
В поле номера телефона необходима маска с кодом США.
При успешной отправке оповестить пользователя любым способом, кроме alert(модальное окно, надпись/картинка снизу и т.д. Аналогично при ошибке.)

- В папке modules создаю файл form.js
- Прописав скрипты не забыть импортировать в main.js

## Многостраничность. Как избегать ошибок в коде

- Открываю вторую страницу проекта и проверяю на наличие ошибок
- Если появляются ошибки, строчки кода оборачиваю в try {} catch(e) {}

## Главный слайдер второй страницы, всплытие событий
Страница modules.html должна быть реализована аналогичным образом. Кроме этого, необходимо реализовать навигацию под контентом модуля.

## Создаем динамический видеоплеер
На странице модулей при клике на кнопку play - показать ролик, аналогичным способом как и в пункте №3. Второй ролик открывается для просмотра только если человек просмотрел первый. До этого - на нём клик не срабатывает. Также изменить стили при открытии.

- Редактируем код в playVideo.js
 
## Функционал загрузки файлов, разворачивания контента и итоги проекта
Реализовать небольшой аккордеон.
При клике на него - снизу плавно должен появляться небольшой текст-рыба.
При повторном клике - скрываться.

При клике на кнопку Donwload PDF - идёт скачивание файла. Подключите любой, небольшой файл.

- В папке modules создаю файл showInfo.js
- Прописав скрипты не забыть импортировать в main.js

-- В папке modules создаю файл download.js
- Прописав скрипты не забыть импортировать в main.js