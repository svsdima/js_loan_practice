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