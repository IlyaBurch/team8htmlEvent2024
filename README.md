Как запустить проект:
- в терминале вводим `npm i`
- затем `npm run dev`

Для проверки кода JS на стандартизацию:
- `npm run standart`

Для того, чтобы автоматически привести код к стандартам:
- `npm run lint`

Из использованного - только линтеры и Sass, все остальное писалось ручками:)

Адаптив - совсем чутка сделали, только для десктопа и то не везде ровно, мобилку даже не пытались

В хэдере :
-есть анимация меню в зависимости от открытой части сайта (работает не везде, не успел чутка из-за проблем с гитом поставить якоря везде и пофиксить наплыв хэдера)
-все остальные ссылки работают - включая отправку имейла и звонок (кнопка рядом с номером телефона рабочая)

В About Us:
-стрелочки функциональны - переключают активный слайд

В Our Company Status:
-работает ховер на все карточки

В Our Projects:
-так же функционируют стрелочки - не совсем корректно, но они переключают так же выбранный слайд без его перемещения

В How to process:
-Переключаются табы, но к сожалению добавить рабочее переключение видео и сделать картинки не успел - из рабочего открывается модалка через `<dialog>`


